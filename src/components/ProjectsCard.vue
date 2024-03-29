<template>
<div class="main-container">
        <div>
        <div class="project-card" v-for="(items, index) in projectData.ProjectsArray" v-bind:key="items">
            <h2> {{projectData.ProjectsArray[index].Title}}</h2>
            <img :src="projectData.ProjectsArray[index].Image" alt="">
            <p> {{projectData.ProjectsArray[index].About}}</p>
            <div class="links">
                <a :href="projectData.ProjectsArray[index].Link1" target="blank"><img src="../assets/github.jpg" alt=""></a>
                <a :href="projectData.ProjectsArray[index].Link2" target="blank"><img src="../assets/facebook.jpg" alt=""></a>
               
            </div>
        </div>
    </div>
    
    </div>
</template>

<script>
import jsonData from "/projects.json"
export default{
    data(){
        return {
            projectData: jsonData
        }
    }

}

</script>

<style scoped>
.main-container{
display: flex;
justify-content: center;
align-items: center;
flex-wrap: wrap;
}
.project-card{
   
    margin: 5px;
    padding: 10px;
    flex-wrap: wrap;
    background-color: rgb(202, 240, 215);
    border-radius:150px;
    box-shadow: rgb(0, 0, 0,)0px 3px 8px;
}
.project-card img{
height: 15rem;
margin: 8%;
flex-wrap: wrap;
}
.links{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
}
.links img{
    
    height: 2rem;
    margin: 5px;
   
}
</style>
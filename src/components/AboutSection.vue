<template>
    <div class="about-parent">
        <h1 class="about-text-1">ABOUT</h1>
        
        <p class="about-text-2">
            at Hack WashU, you'll meet fellow hackers from around the country, learn new skills, and work alongside seasoned mentors.  
            <br> 
            <br>     
            we'll have free workshops, lecture series, mentorship, prizes, games, and more. 
            <br>
            <br>
            don't have a team, or even an idea? don't worry. we'll give you the tools to build something incredible.
        </p>
    </div>
    <img id="meteor-about" src="/src/assets/meteor.png" alt = Image>
    <img id="s1-about" src="/src/assets/star1.png" alt="star">
</template>
 
<style scoped>

#s1-about{
    position: absolute;
    left: 64.583vw;
    top: 58vw;
    width: 15vw;
    height: 15vw;

}

#meteor-about{
    position: absolute;
    left: 10.694vw;
    top: 40vw;
    width: 15vw;
    height: 15vw;
}

.about-parent{
    position: relative;
    height: 34vw;
    display: flex;
    width: 100vw;
}

.about-text-1{
    width: 100vw;
    position: absolute;
    text-align: center;
    font-family: 'FancyFont', serif;
    font-size: 6vw;
}

.about-text-2{
    position: absolute;
    top: 12vw;
    text-align: center;
    font-size: 1.8vw;
    width: 60vw;
    left: 20vw;
    font-family: 'spartan', sans-serif;
}

</style>

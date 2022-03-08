<template>
    <header id="container-header">
        <div id="container-intro">
            <img src="../assets/inevent-go-beyond.png" alt="logo-go-beyond" id="logo-go-beyond">
            <p>InEvent is the most powerful software for professional events.
                If your needs a plataform for B2B events, video-driven conferences,
                or any virtual or hybrid experience. InEvent is the perfect solution
            </p>
            <div id="container-book-meeting">
                <input type="text" id="input-email" placeholder="Enter your email">
                <button id="btn-meeting">Book a meeting</button>
            </div>
        </div>
        <div id="container-video">
            <video autoplay muted loop playsinline preload id="container-video">
                <source src="https://cdn.inevent.com/images/home/header.mp4" type="video/mp4">
                <source src="https://cdn.inevent.com/images/home/header.webm" type="video/webm">
            </video>
        </div>
        
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
    #container-header{
        background-color: #2A333C;
        width: 100vw;
        height: 800px;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        gap: 20px;
    }
    #container-intro{
        width: 570px;
        display: flex;
        flex-direction: column;
        gap: 35px;
    }
    #logo-go-beyond{
        width: 315px;
        height: 80px;
    }
    p{
        color: #FEFEFE;
        font-size: 19px;
    }
    #input-email{
        width: 325px;
        height: 40px;
        background-color: #222930;
        padding: 10px 0px 8px 20px;
        border-radius: 5px;
        border: none;
        outline: none;
        color: #FEFEFE;
    }
    #btn-meeting{
        width: 155px;
        height: 40px;
        background-color: #25A9E0;
        color: white;
        padding: 11px;
        border-radius: 5px;
        border: none;
        font-size: 18px;
        text-align: center;
    }
    #btn-meeting:hover{
        cursor: pointer;
        opacity: 0.8;
        transition: 0.5s;
    }
    #container-video{
        width: 570px;
        height: 570px;
    }
    #container-book-meeting{
        display: flex;
        flex-direction: row;
        align-items: center;
    }
</style>
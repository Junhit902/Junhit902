# Thiago Jun Honma <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGJraHVvMGM1bzh4am03NHFocXpkNjd2dThrMTF0NXk4eHpxaTJ0NSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/78XCFBGOlS6keY1Bil/giphy.gif" width="50" height="50" style="vertical-align: middle;"/>

## SOBRE MIM / ABOUT ME
<div id="about_me">
    <p id="text">👋 Hi, I'm Thiago Jun Honma. I am passionate about developing my skills in programming.</p>
    <button onclick="traduzir">🇧🇷 Português / 🇺🇸 English</button>
</div>

<script>
    function traduzir() {
        var text = document.getElementById("text");
        if (text.innerHTML.includes("Hi, I'm Thiago")) {
            text.innerHTML = "👋 Olá, sou Thiago Jun Honma. Sou apaixonado por desenvolver minhas habilidades em programação.";
        } else {
            text.innerHTML = "👋 Hi, I'm Thiago Jun Honma. I am passionate about developing my skills in programming.";  
        }
    }
</script>
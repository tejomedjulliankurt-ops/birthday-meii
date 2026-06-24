<div id="message" class="message">
    <h1>🎂 HAPPY BIRTHDAY MEII! 🎂</h1>

    <p style="font-size:18px; line-height:1.8;">
        hiiiii bbyyyyyyy, luvluv, honeybunchsugarplum, love, and many more call signs
        HAHAHAHAHAHAHAHA.
        <br><br>
        pero bet ko an love HAHAHAHAHAHAHAHAHA.
        okay amo tak gagamiton na call sign yana.
        <br><br>
        🤩🤩🥳🥳🎉💝💝
        <br><br>
        HAPPPPPPYYYYYY HAPPPYYYYY BIRTHDAYYYYYY MYYYY LOVEEEEEEE!!
        <br><br>
        HAPPYYYY LEGALITY!
        Finally, diri na me paedophile
        (tawa kay joke ito 😂)
        hehe.
        <br><br>
        I luvvvvvv uuuuuuu sooo much love!
        <br><br>
        Mwaaaaaaaaa 😚😚😚😚😚
    </p>

    <h2>❤️ Love Always ❤️</h2>
    <p><b>Bbyyyyyyy</b></p>
</div><style>
.heart{
    position:fixed;
    bottom:-20px;
    font-size:24px;
    animation:float 8s linear infinite;
    pointer-events:none;
}

@keyframes float{
    0%{
        transform:translateY(0);
        opacity:1;
    }
    100%{
        transform:translateY(-110vh);
        opacity:0;
    }
}
</style>
<script>
setInterval(() => {
    const heart = document.createElement("div");
    heart.className = "heart";
    heart.innerHTML = "💖";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (20 + Math.random() * 25) + "px";
    document.body.appendChild(heart);

    setTimeout(() => {
        heart.remove();
    }, 8000);
}, 400);
</script>
<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.3/dist/confetti.browser.min.js"></script>

<script>
function openGift(){
    document.getElementById("gift").style.display="none";
    document.getElementById("message").style.display="block";

    confetti({
        particleCount:200,
        spread:120,
        origin:{ y:0.6 }
    });
}
</script>



Copy code
<h1>Hi there! <span class="wave">👋</span></h1>

<style>
.wave {
    animation-name: wave-animation;
    animation-duration: 2.5s;
    animation-iteration-count: infinite;
    transform-origin: 70% 70%;
    display: inline-block;
}

@keyframes wave-animation {
    0% { transform: rotate(0deg) }
    10% { transform: rotate(14deg) }
    20% { transform: rotate(-8deg) }
    30% { transform: rotate(14deg) }
    40% { transform: rotate(-4deg) }
    50% { transform: rotate(10deg) }
    60% { transform: rotate(0deg) }
    100% { transform: rotate(0deg) }
}
</style>

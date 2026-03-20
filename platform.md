---
layout: page
title: Platform
subtitle: How I'll Make a Difference as Your Secretary of Local Impact
---

**I will…**

- Directly connect you and your clubs to people in town with similar interests + cultural experiences.
  
*My role is to see what you all need/want and bring you together in community with those that feel similarly, or that you could benefit from having relationships with. I will create a linking system that makes this simple and fun!* 

- Provide you with mutual aid opportunities in town.
  
*Mutual aid is a way to help your community through direct action. This could look like grocery runs, help with moving out, driving kids to school, or teaching someone a new skill.* 

- Educate students on local issues.
  
*Making an impact requires respect and compassion, so let’s learn from one another about culture, struggles, and ways to best interact with community so we can go in ready to make change.*

___

<style>
    .bg {
        width: 100vw;
        aspect-ratio: 1325/2048;
        position: fixed;
        margin: 0;
        padding: 0;
        left: 0;
        top: -15vh;
        z-index: -10;

        background-image: url("/assets/img/borders.png");
        background-repeat:no-repeat;
        background-size: cover;
        /*background-color: rgb(224, 232, 224);*/

    }

    
    @media (max-width: 560px) {
        .bg {
            display: none;
        }
    }
</style>
<div class="bg" id="bg">

<script>
document.addEventListener("DOMContentLoaded", function () {
    
var layer = document.getElementById("bg");

var y = 0;

var h = window.innerHeight;
var lastpos = 0;

function animate(event) {
    var dir = lastpos - event.touches[0].clientY;
    lastpos = event.touches[0].clientY;
	

	y -= .2*dir;
	y = Math.min(y, 0);
	y = Math.max(y, h - layer.clientHeight);
	layer.style.top = y+"px";
}
window.addEventListener('wheel', animate);
});
</script>
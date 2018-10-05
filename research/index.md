---
title: Research
---
<style>
.iconDetails {
	width:30%;
    height:30%;
	float:left;
	max-height:250px;
	max-width:250px; 
	border-radius: 5px;
} 

.container {
    width:100%;
    height:24%;
    padding:1%;
}
h4 {
    margin:0px;
}
</style>

<script>
function toggleAbstract(btn) {
    var x = btn.nextElementSibling;
    if (x.innerHTML === "") {
        x.innerHTML = x.getAttribute("text");
    } else {
        x.innerHTML = "";
    }
}
</script>

<div class='container'>
    <div>
	<img src='{{ site.url }}images/research-modeling.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:35%;'>
    <h4>User modelling for personalised and co-adaptive human-robot interaction</h4>
    Simulating the tremendous social adaptation abilities that characterise human interactions requires the establishment of bidirectional processes in which humans and robots synchronise and adapt to each other in real-time by means of a mutual exchange of verbal and non-verbal behaviours in order to achieve mutual co-adaptation. The ability to respond in a contingent manner to users’ needs, preferences, interests, intentions and emotions is, in fact, of paramount importance to achieve long-term robot autonomy, that is, to establish and maintain autonomous interactions with human users over extended periods of time. To endow robots with co-adaptation abilities, a typical approach leverages statistical learning to incrementally adapt robot’s behaviours and strategies to a specific user’s situation, for example, a user’s emotion, personality or progress with a task. This affect-based, personalised co-adaptation aims to close the human-machine loop while enabling robot learning from human users in more natural, intuitive ways.

    </div>
</div>

<div class='container'>
    <div>
	<img src='{{ site.url }}images/research-synergies.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:35%;'>
    <h4>Synergies between robot appearance, behavior and quality of the interaction</h4>
    <div style="font-size:.8em"> The physical body and appearance of a robot is at the heart of the effectiveness of socially-assistive roles due to innate human tendencies to engage with lifelike, emotional social behaviour and forms, developing social impressions and bonds based on various qualities of the physical body and how they relate to the individual. A key challenge here is to explore synergies between robot appearance and behaviour and quality of the interaction perceived by human users. For example, one important aspect in building likable social robots is to ensure that humans do not feel uncomfortable during the interaction or perceive the robot as uncanny. We investigate how the design of a robot’s appearance qualities and behaviours, as well as their synergies, affect the emergence of the uncanny valley phenomenon.</div>

    </div>
</div>

<div class='container'>
    <div>
	<img src='{{ site.url }}images/research-social.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:35%;'>
	<h4>Social learning</h4>
	<div style="font-size:.8em"> In order to successfully cooperate with humans, robots need to learn new skills and behaviours from them, for example, through gesture and speech. This type of social learning, achieved in a social context, may be facilitated by humans acting as teachers, in an implicit or explicit manner. The challenge here is to develop new statistical learning methods for social learning that find an optimal level of human intervention in the robot learning process. By adopting a breadth-first, holistic approach that integrates interdisciplinary research on social robotics and machine learning grounded in principles from the social sciences, the objective of this research is to develop computational social abilities that allow robots to behave in a socially intelligent way.</div>
    </div>
</div>

<div class='container'>
    <div>
	<img src='{{ site.url }}images/research-education.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:35%;'>
	<h4>Educational robots</h4>
	<div style="font-size:.8em"> Robotics is now one of a few technologies that have the potential to have an impact over the next few decades similar to the one that the Internet has today. One of the main reasons is that new robotics applications are extending the role of robots beyond jobs that humans do not want or cannot do to socially assistive scenarios that aim to help people in more personal ways and provide not only physical, but also social support. In this context, we investigate how robots can be used as educational agents to support students’ learning. In addition to the technological advancements required to achieve this objective, we are interested in how robots can be used as a support for teachers in a classroom environment and how they can be integrated in the design of new engaging scenarios for learning.</div>
    </div>
</div>

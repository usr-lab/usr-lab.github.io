---
layout: post
title: People
---
<style>
.iconDetails {
	float: left;
	width:20%;
    	height:20%;
	max-height:150px;
	max-width:150px; 
	border-radius: 10px;
} 

.container {
    width:100%;
    height:24%;
}
h4 {
    margin:0px;
}
.button {
    clear: left;
    background-color: #4CAF50; /* Green */
    border: none;
    color: white;
    padding: 4px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 12px;
    margin: 4px 2px;
    -webkit-transition-duration: 0.4s; /* Safari */
    transition-duration: 0.4s;
    cursor: pointer;
}

.green {
    background-color: white; 
    color: black; 
    border: 2px solid #4CAF50;
}

.green:hover {
    background-color: #4CAF50;
    color: white;
}

.blue {
    background-color: white; 
    color: black; 
    border: 2px solid #008CBA;
}

.blue:hover {
    background-color: #008CBA;
    color: white;
}

.red {
    background-color: white; 
    color: black; 
    border: 2px solid #f44336;
}

.red:hover {
    background-color: #f44336;
    color: white;
}

.gray {
    background-color: white;
    color: black;
    border: 2px solid #e7e7e7;
}

.gray:hover {background-color: #e7e7e7;}

.black {
    background-color: white;
    color: black;
    border: 2px solid #555555;
}

.black:hover {
    background-color: #555555;
    color: white;
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

<h3> Ginevra Castellano </h3>
<h4 style="color:grey"> Associate Professor </h4>
<h4 style="color:grey"> Lab Director </h4>
<div class='container'>
    <div>
		<img src='../images/people-ginevra.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:25%;'>
    <div style="font-size:.8em"> Ginevra Castellano is an Associate Professor at the Department of Information Technology, Uppsala University, where she leads the Social Robotics Lab. Her research interests are in the areas of social robotics and affective computing, and include social learning, personalized adaptive robots, multimodal behaviours and uncanny valley effect in robots and virtual agents. Over the last ten years she has been working on the development of computational abilities that allow robots to behave in a socially intelligent way in scenarios where robots provide social support to humans, for example as tutors in the classroom or as companions for children.</div>
    </div>
</div>
<p style="clear:both;"></p>
<button class="button black" onclick="window.open('http://user.it.uu.se/~ginca820/')" type="button">
	Ginevra Castellano's Personal Website</button>

<h3> Giulia Perugia </h3>
<h4 style="color:grey">  Postdoc Researcher </h4>
<div class='container'>
    <div>
		<img src='../images/people-giulia.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:25%;'>
    <div style="font-size:.8em"> Dr. Giulia Perugia received a BA in Literature and Linguistics from the University of Roma Tre (Rome, Italy) in 2011, a MSc in Cognitive Science from the University of Siena (Italy) in 2013, and a double degree PhD in Assistive Technologies from the Polytechnic University of Catalonia (UPC; Barcelona, Spain) and Eindhoven University of Technology (TU/e; Netherlands) in 2018. In November 2018, she joined the Social Robotics Lab at Uppsala University (Sweden) as a postdoctoral researcher. As a scientist, she is interested in understanding and modeling the emotional and social linkage that the interaction with social robots triggers, how this can be used for assistive and educational purposes, and how it might impact and shape our society. </div>
    </div>
</div>
<p style="clear:both;"></p>
<button class="button black" onclick="window.open('http://katalog.uu.se/profile/?id=N18-2160')" type="button">Giulia Perugia's Website</button>
<!--
<h3>Mohammad Obaid</h3>
<h4 style="color:grey"> Visiting Researcher </h4>
<div class='container'>
    <div>
		<img src='../images/people-mohammad.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:25%;'>
    <div style="font-size:.8em"> Dr. Mohammad Obaid received his BSc., MSc. (First Class Honors) and Ph.D. degrees in Computer Science from the University of Canterbury, Christchurch, New Zealand, in 2004, 2007 and 2011, respectively. He worked at several international research centers including the Human Centered Multimedia Lab (HCM Lab), University of Augsburg (Germany), the Human Interface Technology Lab New Zealand (HITLab NZ), University of Canterbury (New Zealand), and the t2i Lab, Chalmers University of Technology (Sweden). In 2016, he joined the the Social Robotics Lab, Department of Information Technology, Uppsala University (Uppsala, Sweden) as a researcher.</div>
    </div>
</div>
<p style="clear:both;"></p>
<button class="button black" onclick="window.open('http://t2i.se/mohammad-obaid/')" type="button">
	Mohammad Obaid's Personal Website</button>
-->
<h3> Maike Paetzel </h3>
<h4 style="color:grey">  Ph.D. Candidate </h4>
<div class='container'>
    <div>
		<img src='../images/people-maike.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:25%;'>
    <div style="font-size:.8em"> Maike Paetzel is a PhD student in the Social Robotics Lab and mainly focused on studying the uncanny valley effect. She is specifically interested in how interactions with an agent can change an initial (uncanny) perception. Maike’s background is both in humanoid robotics and conversational agents. Apart from Human-Robot Interaction her heart belongs to the RoboCup community, where she is still actively engaged in the team Hamburg Bit-Bots and the organization of the Humanoid League.</div>
    </div>
</div>
<p style="clear:both;"></p>
<button class="button black" onclick="window.open('https://maike-paetzel.de/')" type="button">
	Maike Paetzel's Personal Website</button>

<h3> Alex Yuan Gao </h3>
<h4 style="color:grey">  Ph.D. Candidate </h4>
<div class='container'>
    <div>
		<img src='../images/people-alex.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:25%;'>
    <div style="font-size:.8em"> (Alex) Yuan Gao is a Ph.D. candidate at Uppsala University. His research interests are driven by a final goal of developing AI-driven robots that can think and feel like real humans (e.g. Ex Machina). This encircles robot's learning and control, nature language processing, image processing, neuroscience and computational phycology. In particular, he is interested in deep/reinforcement/neuro-based learning approaches to robotic perception, control, and physical modeling of the robot’s environment, which can help us to understand ourselves and build a unified learning structure for adaptive, efficient and robust complex robotic system. Currently, he is working on projects that can fill the gap between deep reinforcement learning and social robotics.</div>
    </div>
</div>
<p style="clear:both;"></p>
<button class="button black" onclick="window.open('http://yuangao.ai')" type="button">
	Yuan Gao's Personal Website</button>

<h3>Sebastian Wallkötter</h3>
<h4 style="color:grey">  Ph.D. Candidate </h4>
<div class='container'>
    <div>
		<img src='../images/people-sebastian.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:25%;'>
    <div style="font-size:.8em"> Sebastian Wallkötter is a PhD student at the Department of Information Technology, Uppsala University, and works as a researcher in the Social Robotics Lab. His work is part of the Horizon 2020 funded ANIMATAS project. He is interested in social learning for robots, ethical behavior of robotic systems as well as advancing the field of machine learning in the areas of reinforcement learning and deep learning.</div>
    </div>
</div>
<p style="clear:both;"></p>
<button class="button black" onclick="window.open('http://sebastian.wallkoetter.net')" type="button">
	Sebastian Wallkötter's Personal Website</button>
	
<h3>Natalia Calvo</h3>
<h4 style="color:grey">  Ph.D. Candidate </h4>
<div class='container'>
    <div>
		<img src='../images/people-natalia.png' class='iconDetails'>
    </div>  
    <div style='margin-left:25%;'>
    <div style="font-size:.8em"> Natalia Calvo is a Ph.D. student in the Social Robotics Lab. She believes in a world where robots can actively assist humans in different scenarios.  Her work is focused on modeling trust in human-robot educational interactions, and it is part of the ANIMATAS Project funded by Horizon 2020. Her research interests cover deep learning and human-robot interaction towards an interdisciplinary approach mostly focused on manipulation tasks, speech recognition interfaces, computer vision, and social robotics.    </div>
</div>
<p style="clear:both;"></p>
<button class="button black" onclick="window.open('http://www.natycalvo.com')" type="button">
	Natalia Calvo's Personal Website</button>	

<h3>Sita Vriend</h3>
<h4 style="color:grey">  Master Student </h4>
<div class='container'>
    <div>
		<img src='../images/people-sita.jpg' class='iconDetails'>
    </div>  
    <div style='margin-left:25%;'>
    <div style="font-size:.8em"> Sita Vriend is a master student in Human-Computer Interaction at Uppsala University and an intern at the social robotics lab. She received a BSc in game architecture and design from the Breda university of applied sciences (the Netherlands). She provides an interesting combination with her experience and knowledge in game design, and her knowledge in usability and UX methods.   </div>
</div>
<p style="clear:both;"></p>
<button class="button black" onclick="window.open('https://sitavriend.wordpress.com/')" type="button">
	Sita Vriend's Personal Website</button>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>EOG Practice Quest: Maya Text Analysis</title>
<style>
:root{
  --mint:#bff7d3;
  --mint2:#e8fff0;
  --dark:#0f4d2f;
  --deep:#08351f;
  --yellow:#ffd85a;
  --brown:#7a4a24;
  --cream:#fff9e8;
  --danger:#a6422b;
  --gold:#f7c843;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;
  font-family: "Trebuchet MS", Arial, sans-serif;
  background: radial-gradient(circle at top left, var(--mint2), var(--mint) 36%, #f9f0cb 100%);
  color:#17351f;
  user-select:none;
  -webkit-user-select:none;
}
button,input,textarea,label{font-family:inherit}
.screen{display:none; min-height:100vh; padding:24px;}
.active{display:block}
.hero{
  position:relative;
  overflow:hidden;
  border:5px solid var(--dark);
  border-radius:30px;
  max-width:1100px;
  margin:20px auto;
  padding:46px 26px;
  background:linear-gradient(145deg,#efffe9,#c9f9d6 55%,#ffe88a);
  box-shadow:0 18px 0 var(--brown),0 24px 40px rgba(0,0,0,.22);
}
.sun{
  position:absolute; right:70px; top:40px; width:145px; height:145px; border-radius:50%;
  background:var(--yellow); box-shadow:0 0 40px #ffef8a;
  animation:pulse 2.7s infinite alternate;
}
@keyframes pulse{to{transform:scale(1.08); box-shadow:0 0 70px #ffef8a}}
.leaf{position:absolute; font-size:36px; animation:float 9s linear infinite; opacity:.75}
.l1{left:4%; top:8%; animation-delay:0s}.l2{left:85%; top:68%; animation-delay:1s}.l3{left:18%; top:75%; animation-delay:2s}.l4{left:65%; top:14%; animation-delay:3s}.l5{left:45%; top:82%; animation-delay:4s}
@keyframes float{0%{transform:translateY(0) rotate(0)}50%{transform:translateY(-28px) rotate(14deg)}100%{transform:translateY(0) rotate(360deg)}}
.hero h1{
  position:relative;
  color:var(--deep);
  font-size:clamp(2rem,5vw,4rem);
  text-shadow:2px 2px 0 #fff, 4px 4px 0 var(--yellow);
  margin:0 0 12px;
}
.hero .subtitle{
  position:relative; max-width:780px; font-size:1.15rem; line-height:1.55; font-weight:bold;
}
.nameBox{
  position:relative; background:#fffdf1cc; border:3px solid var(--brown); border-radius:22px; padding:18px; margin-top:24px; max-width:620px;
}
input[type=text]{
  width:100%; padding:14px; font-size:1.1rem; border:3px solid var(--dark); border-radius:15px; background:white;
}
.mainBtn,.smallBtn{
  border:none; background:linear-gradient(135deg,var(--dark),#168854);
  color:white; font-weight:900; border-radius:18px; padding:14px 22px; cursor:pointer;
  box-shadow:0 7px 0 var(--brown); transition:.15s; margin-top:12px;
}
.mainBtn:hover,.smallBtn:hover{transform:translateY(-2px)}
.mainBtn:active,.smallBtn:active{transform:translateY(5px); box-shadow:0 2px 0 var(--brown)}
.topbar{
  max-width:1250px; margin:0 auto 16px; background:#fffbe8; border:3px solid var(--dark); border-radius:20px;
  padding:12px; display:grid; grid-template-columns:1fr auto; gap:12px; align-items:center; box-shadow:0 6px 0 var(--brown);
}
.progressOuter{height:18px; background:#d5ebd2; border:2px solid var(--dark); border-radius:999px; overflow:hidden}
.progressInner{height:100%; width:0%; background:linear-gradient(90deg,var(--yellow),#6dcc83,var(--dark)); transition:.3s}
.panel{
  max-width:1250px; margin:0 auto; display:grid; grid-template-columns:minmax(0,1.08fr) minmax(340px,.92fr); gap:18px;
}
.card{
  background:#fffdf1; border:3px solid var(--dark); border-radius:24px; padding:18px; box-shadow:0 8px 0 var(--brown);
}
.passage{
  max-height:72vh; overflow:auto; line-height:1.6; font-size:1rem; padding-right:8px;
}
.passage h2{color:var(--deep); margin-top:0}
.passage p{margin:0 0 13px}
.annotation textarea{
  width:100%; height:110px; border:3px dashed var(--brown); border-radius:16px; padding:10px; resize:vertical; user-select:text;
}
.qtitle{font-size:1.12rem; font-weight:900; color:var(--deep); margin-bottom:8px}
.standards{font-size:.85rem; font-weight:bold; color:#406044; margin-bottom:10px}
.option{
  display:block; padding:12px; margin:9px 0; border:2px solid #6da378; border-radius:16px; background:#f8fff5; cursor:pointer; user-select:none;
}
.option:hover{background:#fff6bf}
.option input{margin-right:8px}
.dragWrap{display:grid; grid-template-columns:1fr 1fr; gap:12px}
.dragItem{
  padding:10px; background:#fff6bf; border:2px solid var(--brown); border-radius:13px; margin:7px 0; cursor:grab; font-weight:bold;
}
.dropZone{
  min-height:105px; border:3px dashed var(--dark); border-radius:16px; padding:10px; background:#effff0;
}
.dropZone h4{margin:0 0 8px; color:var(--deep)}
.navBtns{display:flex; justify-content:space-between; gap:10px; margin-top:14px; flex-wrap:wrap}
.warning{color:var(--danger); font-weight:900; min-height:22px}
.reviewItem{
  border-left:7px solid var(--brown); background:#fff8d9; border-radius:14px; padding:12px; margin:10px 0;
}
.cert{
  max-width:900px; margin:30px auto; border:10px double var(--gold); border-radius:28px; padding:35px; text-align:center;
  background:radial-gradient(circle,#fff9cf,#ffe38b 55%,#d09a28);
  box-shadow:0 0 35px rgba(247,200,67,.9),0 13px 0 #8a5c1e;
  animation:shine 2s infinite alternate;
}
@keyframes shine{to{filter:brightness(1.08); transform:scale(1.01)}}
.cert h1{font-size:3rem; color:#6b3f0c; margin:0}
.badge{font-size:4rem; animation:spin 5s linear infinite}
@keyframes spin{to{transform:rotate(360deg)}}
.scoreBig{font-size:2.3rem; font-weight:900; color:var(--deep)}
.footerNote{font-size:.9rem; opacity:.8}
@media(max-width:900px){.panel{grid-template-columns:1fr}.passage{max-height:45vh}.sun{opacity:.35}}
@media print{body{background:white}.screen:not(.active),.noPrint{display:none!important}.cert{box-shadow:none}}
</style>
</head>
<body oncopy="return false" oncut="return false" onpaste="return false" oncontextmenu="return false">

<section id="startScreen" class="screen active">
  <div class="hero">
    <div class="sun"></div>
    <div class="leaf l1">🍃</div><div class="leaf l2">🌿</div><div class="leaf l3">🌽</div><div class="leaf l4">🍯</div><div class="leaf l5">📜</div>
    <h1>EOG Practice Quest</h1>
    <p class="subtitle">Maya Legends, Creation Texts, and Informational Analysis. This challenge uses advanced question stems, close reading, evidence evaluation, structural analysis, and tricky answer choices. Read slowly. Annotate. Prove your thinking.</p>
    <div class="nameBox">
      <label><strong>Enter your full name to begin:</strong></label><br><br>
      <input id="studentName" type="text" placeholder="First and Last Name" autocomplete="off"/>
      <button class="mainBtn" onclick="startGame()">Start the Quest</button>
      <p class="footerNote">Goal: 75% or higher earns the animated golden certificate.</p>
    </div>
  </div>
</section>

<section id="gameScreen" class="screen">
  <div class="topbar">
    <div>
      <strong id="welcome"></strong>
      <div class="progressOuter"><div id="progress" class="progressInner"></div></div>
    </div>
    <div><strong id="counter"></strong></div>
  </div>
  <div class="panel">
    <div class="card">
      <div id="passageBox" class="passage"></div>
      <div class="annotation">
        <h3>Annotation Notes</h3>
        <textarea id="notes" placeholder="Write short notes: theme, tone, structure, evidence, confusing words, author's purpose..."></textarea>
      </div>
    </div>
    <div class="card">
      <div id="questionBox"></div>
      <div class="warning" id="warning"></div>
      <div class="navBtns">
        <button class="smallBtn" onclick="prevQuestion()">← Back</button>
        <button class="smallBtn" onclick="nextQuestion()">Next →</button>
        <button class="smallBtn" onclick="finishGame()">Submit Final</button>
      </div>
    </div>
  </div>
</section>

<section id="resultScreen" class="screen">
  <div class="card" style="max-width:1000px;margin:25px auto;">
    <h1>Final Results</h1>
    <p id="finalScore" class="scoreBig"></p>
    <div id="certificate"></div>
    <h2>Questions to Review</h2>
    <p><strong>Important:</strong> The correct answers are not shown. Use the interpretation notes to reread, rethink, and revise your strategy.</p>
    <div id="review"></div>
    <button class="mainBtn noPrint" onclick="location.reload()">Restart Practice</button>
  </div>
</section>

<script>
document.addEventListener('keydown', function(e){
  if((e.ctrlKey || e.metaKey) && ['c','v','x','a','s','p','u'].includes(e.key.toLowerCase())) e.preventDefault();
});

const passages = [
{
title:"Text 1: The Legend of the Aluxes",
html:`<h2>Text 1: The Legend of the Aluxes</h2>
<p>For generations, deep within the emerald forests of the Yucatán Peninsula in Mexico, the people of the ancient Maya spoke in hushed voices about the Aluxes—small, mysterious beings who lived between the roots of ceiba trees, inside hidden caves, and near sacred cenotes where the stars reflected in the still water.</p>
<p>The Aluxes were not ordinary creatures. They were said to be no taller than a child’s knee, with bright eyes that glowed silver in the moonlight and pointed ears sharp enough to hear the secrets of the wind. Some wore tiny woven hats and cloaks made of leaves, while others looked like little old men with wrinkled faces and wise smiles. They could appear and disappear as they pleased, slipping between shadows, becoming birds, foxes, or nothing more than a whisper in the trees.</p>
<p>The Maya believed the Aluxes were the protectors of nature.</p>
<p>They guarded the forests, the animals, the rivers, and the crops that fed the people. They also watched over ancient temples and sacred ruins, ensuring no one disturbed the resting places of the ancestors. To disrespect the land was to invite the anger of the Aluxes. To honor it was to receive their blessing.</p>
<p>In a small village near the jungle lived a young farmer named Teyo.</p>
<p>Teyo was hardworking, gentle, and deeply respectful of the old ways. He had learned from his grandmother, Nana Ixchel, who was the oldest storyteller in the village and keeper of many ancient traditions. Every evening, children gathered around her fire to hear stories of the old gods, sacred spirits, and the tiny forest guardians.</p>
<p>“The land listens,” Nana Ixchel often told Teyo. “And the Aluxes listen with it. If you take from the earth, you must also give back.”</p>
<p>Teyo believed her.</p>
<p>Before planting corn, he pressed his hands into the soil and whispered thanks. Before cutting wood, he asked permission from the trees. At the edge of his field, he left small offerings—fresh maize, honey, cacao beans, and bowls of cool water.</p>
<p>Some villagers admired him for this.</p>
<p>Others laughed.</p>
<p>Especially Baltun.</p>
<p>Baltun was the wealthiest man in the village and owner of the largest farmland. Unlike Teyo, Baltun cared little for stories or spirits. He believed only in power, money, and control. Tall, proud, and always dressed in fine woven cloth, he often spoke as if he were above everyone else.</p>
<p>He had once been poor as a child, and he swore he would never be powerless again. Success had hardened him. Where others saw sacred forests, Baltun saw unused land. Where others saw ancient ruins, he saw stones in the way of expansion.</p>
<p>“Corn grows from work, not from feeding invisible creatures,” Baltun would scoff.</p>
<p>Still, despite his wealth, something bothered him.</p>
<p>Teyo’s crops were thriving.</p>
<p>Even during dry months, Teyo’s corn stood tall and golden. His beans climbed strong, and his squash spread wide and healthy across the soil. Meanwhile, Baltun’s larger fields often struggled with insects, poor harvests, and cracked earth.</p>
<p>Jealousy began to grow inside him like a poison vine.</p>
<p>One afternoon, Baltun stood at the edge of Teyo’s farm, watching workers gather heavy baskets of corn.</p>
<p>“You could double this land,” Baltun said. “Sell more. Build more. Why stay small?”</p>
<p>Teyo wiped sweat from his brow and smiled.</p>
<p>“Because the land gives what it is ready to give. Taking too much brings imbalance.”</p>
<p>Baltun laughed sharply.</p>
<p>“Balance does not feed ambition.”</p>
<p>“No,” Teyo replied calmly, “but greed destroys what feeds us.”</p>
<p>Baltun walked away angry, but the words stayed with him.</p>
<p>That same week, Baltun announced his plan. He would clear part of the nearby forest beyond the sacred cenote and build new fields there. It was fertile land, untouched for generations.</p>
<p>The village elders were horrified. “That forest protects the old temple ruins,” warned Nana Ixchel. “The Aluxes guard that place.”</p>
<p>Baltun rolled his eyes. “Stories for children.”</p>
<p>Even Teyo tried to reason with him. “That place is sacred. Leave it untouched.”</p>
<p>But Baltun’s pride would not bend. “Then watch me succeed where fear has made all of you weak.”</p>
<p>The next morning, workers entered the forest with axes. The first tree fell with a sound so loud it echoed like thunder. Birds exploded into the sky. The wind changed. And from somewhere deep in the trees came a sound like distant laughter.</p>
<p>The workers froze. Baltun shouted for them to continue. But strange things began almost immediately. Axes vanished. Ropes untied themselves. Oxen refused to move forward. Freshly cut wood was found stacked neatly back where it had been taken. At night, tiny footprints circled Baltun’s house. His dogs barked at empty corners. Children reported seeing glowing eyes watching from the fields.</p>
<p>Still, Baltun refused to stop. Instead, he grew angrier. “Someone is playing tricks on me!”</p>
<p>One evening, after another ruined workday, Baltun stormed into the village square demanding answers. The elders stayed silent. Only Nana Ixchel spoke. “The forest is warning you.”</p>
<p>“No,” Baltun snapped, “people are trying to frighten me.”</p>
<p>She looked at him sadly. “No, Baltun. You are frightening yourself by refusing to listen.”</p>
<p>That night, determined to prove everyone wrong, Baltun took a lantern and hid alone in the new field. He would catch whoever was sabotaging his land.</p>
<p>Midnight came. The jungle was silent. Then he heard it. Soft laughter. Light and musical, like wind chimes moving in the dark. Tiny shadows danced between the corn stalks. Baltun leaped forward. “Show yourselves!”</p>
<p>The wind rose suddenly. His lantern blew out. Darkness swallowed everything. The field disappeared beneath his feet. He ran, but every path twisted. Trees seemed to move. Roots reached like fingers. Voices whispered from every direction.</p>
<p>Hours passed. Fear replaced anger. Finally, exhausted, Baltun stumbled into a clearing lit by moonlight. There stood the ancient temple ruins. Vines wrapped around old stones carved with faces of forgotten kings and gods. The air felt heavy, alive. And on the broken steps stood dozens of Aluxes.</p>
<p>Their eyes glowed like stars. Their leader stepped forward—a small figure with silver hair, a carved staff, and a face both ancient and young.</p>
<p>“You have entered a place your ancestors protected,” he said, his voice like leaves rustling before rain.</p>
<p>Baltun trembled. “So…you are real.”</p>
<p>The Alux leader tilted his head. “Did you think respect depended on belief?”</p>
<p>Baltun had no answer.</p>
<p>“You take without gratitude,” the Alux continued. “You destroy what you do not understand. You seek wealth while starving your spirit.”</p>
<p>Baltun’s voice shook. “I only wanted security. I grew up with nothing. I thought if I had enough land, enough success… I would never feel small again.”</p>
<p>For the first time, his anger sounded like sadness. The Alux leader stepped closer. “And yet you have never felt satisfied.”</p>
<p>Baltun lowered his head. It was true. The wealth had not brought peace. Only hunger for more. He fell to his knees. “I was wrong. I see that now. Please…tell me how to make it right.”</p>
<p>For a long moment, only the forest answered. Then the Alux leader pointed toward the ruins. “These stones carry memory. These trees carry breath. This land carries your future. To repair harm, you must protect what remains.”</p>
<p>Baltun nodded, tears stinging his eyes. “I will.”</p>
<p>When dawn arrived, Baltun awoke at the edge of the village, covered in leaves and dust. He said nothing at first. But everyone noticed the change.</p>
<p>He stopped the clearing. He paid workers to replant the trees. He repaired the path to the sacred ruins and placed stones to protect the old temple walls. He left offerings at the edge of his fields.</p>
<p>And one evening, quietly, he sat beside Teyo. “I thought strength meant owning everything,” Baltun admitted.</p>
<p>Teyo handed him a piece of roasted corn. “And now?”</p>
<p>Baltun looked toward the forest. “Now I think strength means knowing what should never belong to you.”</p>
<p>Teyo smiled. Nana Ixchel, watching from her doorway, smiled too.</p>
<p>That year, Baltun’s harvest improved—not larger, but healthier. His fields no longer fought against him. Peace returned to the village. Some nights, tiny laughter could still be heard near the cenote. Sometimes bowls of honey left at the forest edge were found empty by morning. And children swore they saw little footprints near the ruins after the rain.</p>
<p>The elders would simply nod. “The Aluxes are still watching.”</p>
<p>And so the legend lived on—not merely as a story of magical beings, but as a lesson. Nature is not ours to conquer. History is not ours to erase. The earth remembers how we treat it. And somewhere beneath the moonlit trees, among sacred stones and whispering leaves, the Aluxes still walk—small guardians of balance, protecting the land for those wise enough to respect it.</p>`
},
{
title:"Text 2: Versions from the Popol Vuh: An Excerpt",
html:`<h2>Text 2: Versions from the <em>Popol Vuh</em>: An Excerpt</h2>
<p><strong>By Unknown</strong></p>
<p>And here in this root-place we call K’iche’<br>
we’re going to write down the words,<br>
we’re going to write down the ancient words,<br>
which are the source of everything done<br>
here in this root-place called K’iche’.</p>
<p>And we’re going to teach, tell, show how<br>
the world was made, how light was brought<br>
by the Maker, the Shaper,<br>
the Sustainer, the Origin who is named<br>
Hunahpu Possum, Hunahpu Coyote,<br>
Great White Peccary, Wide-Eyed Coati,<br>
Lofty Feathered Snake, Heart of the Lake,<br>
Heart of the Sea, Great Potter<br>
of Plate and Bowl, and also called Midwife,<br>
Matchmaker, Gatherer, named Xpiyacoc,<br>
Xmucane, Guardian, Sponsor,<br>
two times a midwife, two times a matchmaker—<br>
all told as the story is told in K’iche’.</p>
<p>They made everything, thought of everything,<br>
and they did it with the clarity of their being,<br>
with the clarity of their words.</p>
<p>And we’re going to write about this now<br>
even as Christianity spreads around us,<br>
even as they talk about the one God.</p>
<p>We’re going to write these words down now<br>
because there’s no longer<br>
anywhere to find them, no Popol Vuh,<br>
no place to see the light beyond the sea,<br>
the story of our lives in the place of shadows,<br>
the story of the beginning of things here.</p>
<p>And we’re going to write this down<br>
from the original book, because those who<br>
would teach it have hidden themselves.</p>
<p>It will take a long time, a long writing<br>
to adequately relate how the sky was lit<br>
and earth covered. To relate the fourfold<br>
cornering, measuring, staking, halving the cord,<br>
stretching the cord across the sky,<br>
across the earth, from corner to corner,<br>
says the ancient book, by the Maker,<br>
the Shaper, the parent of existence,<br>
laborer, provider of breath, of blood,<br>
sustainer, nurturer in the light, bringer<br>
of the light, worrier, knowing custodian<br>
anywhere there are skies, anywhere<br>
there are earthly lakes and seas.</p>`
},
{
title:"Text 3: Who were the Maya? Decoding the ancient civilization’s secrets",
html:`<h2>Text 3: Who were the Maya? Decoding the ancient civilization’s secrets</h2>
<p><strong>The pyramid-building Maya reigned over much of Central America. Today, descendants keep Maya history alive—a sign of resilience.</strong></p>
<p><strong>By Erin Blakemore<br>Last updated October 9, 2025</strong></p>
<p>Evidence of Mayan civilization was everywhere: Beneath a Spanish convent, underneath a street. Most of it was covered in vines and vegetation, reclaimed by the jungle. The British-American explorers combing through the Yucatán Peninsula in the 1830s and 1840s had no idea who built these mysterious sites but soon became convinced that they were major archaeological treasures.</p>
<p>Discarded and abandoned, the function of these sites and artifacts—temples, pyramids, remnants of art and even writing—was mostly unknown. Nonetheless, wrote John Lloyd Stephens in 1841, they all seemed to be the work of the same group of people.</p>
<p>“Who these races were, whence they came, or who were their progenitors, I did not undertake to say, nor did I know,” he conceded. The Maya were a towering Mesoamerican civilization that had once covered much of Central America, from northern Belize through Guatemala and southern Mexico.</p>
<p>Much more is now known about the group responsible for some of the greatest feats of its kind. Maya people cultivated the region’s first crops and domesticated wildlife, built its first cities, and either created or refined almost every aspect of modern civilization.</p>
<p>Though their descendants have preserved some of their culture’s traditions and lore, much of the history of the Maya remains as mysterious today as it did centuries ago when their secrets were still hiding in plain sight.</p>
<p><strong>Origins of the Maya</strong></p>
<p>While the origins of Maya culture remain murky, it’s thought to have first emerged between 7000 B.C. and 2000 B.C., when hunter-gatherers abandoned their nomadic habits and created more permanent settlements.</p>
<p>Recent analyses suggest that those first settlers came from South America and likely developed their staple food, maize, by 4000 B.C. Maize cultivation dramatically changed the Maya’s trajectory, literally fueling the explosion of their society and culture. These newcomers didn’t just plant corn, they also learned to prepare it for human consumption. They did this with nixtamalization, a process in which dried maize is soaked, then cooked in an alkaline solution that softens corn and renders it more digestible. The Maya would go on to cultivate other important vegetables like squash, cassava, and beans.</p>
<p>The Maya seem to have developed alongside, and traded ideas with, the neighboring Olmec civilization, which some consider one of the most influential societies of ancient times. Researchers believe this is when the Maya adopted the ritual complexes for which they would become famous. Like the Olmec, ancient Maya soon focused on building cities around their ritual areas. These advancements in agriculture and urban development are now known as the Maya’s Preclassic period between 1500 and 200 B.C.</p>
<p>As Maya society further developed, they laid the foundations for complex trade routes, advanced irrigation, water purification and farming techniques, warfare, sports, writing, and a complex calendar. The intricate Mayan calendar included three dating systems—one for the gods, one for civil life, and a third astronomical calendar known as the Long Count. The starting point of this third calendar was set at the legendary date of humans’ creation, corresponding to August 11, 3114 B.C.</p>
<p>The Long Count calendar began a new cycle on December 21, 2012, leading to a myth that the world would end on that date. Despite urban legends and longstanding misinterpretations of Maya lore, however, the shift in calendar cycle didn’t bring doomsday with it.</p>
<p><strong>Key achievements</strong></p>
<p>During the Classic Maya period (200-900 A.D.), the Maya civilization reached its peak. So did its architecture. The Maya refined its pyramid-like temples and grand buildings that appear to be palaces, though it’s unclear if they were actually used as elite residences or if they served some other function.</p>
<p>Among the most important Maya cities were Palenque, Chichén Itzá, Tikal, Copán, and Calakmul. But though the Maya shared a society, it was not an empire. Instead, city-states and local rulers vacillated between peaceful coexistence and wrestling for control. Some places, such as the village of Joya de Cerén, seem to have been run by collective rule instead of an elite overlord.</p>
<p>Maya architecture and art reflected deep-seated religious beliefs. The Maya embraced the belief of K’uh and k’uhul—that divinity could be found in all things, even inanimate objects.</p>
<p>Once again, corn was vital to those beliefs. Among the most important Maya gods was Hun Hunahpu, the maize god, and Maya tradition held that the deities created humans first out of mud, then wood, then corn.</p>
<p>The Maya worshiped their gods with a variety of rituals. Among them were both human sacrifice and bloodletting—customs that capture modern imaginations. The Maya sport of pitz, a forerunner of soccer, had its own ritual implications. Researchers think losers of the game were sometimes sacrificed in recognition of the Maya sun and moon gods, who were said to have played the same game in the Maya creation myth, the Popol Vuh.</p>
<p><strong>Decline of the Maya civilization</strong></p>
<p>Although some northern cities continued to flourish, the majority of Maya centers began to collapse during the ninth and tenth centuries A.D. Inter-city relations soured, warfare increased, trade declined, and the death rate rose.</p>
<p>Theories as to the civilization’s demise vary. One hypothesis, backed by climate simulations, is that a long drought—combined with slash-and-burn farming techniques that destroyed the forests upon which the Maya relied—are what brought disaster to their doorstep.</p>
<p>Suddenly, once wealthy city centers became deserted wastelands as some people died and others scattered to a variety of more fertile, mountainous lands to the south. As once massive cities like Chichén Itza fell, cities like Mayapán rose in prominence. Other Maya people abandoned cities altogether, settling into small villages instead.</p>
<p>Though the Maya people persisted, the downfall of Maya civilization left those who remained vulnerable to the pressures of European colonization beginning in the 1500s. By the Spanish conquest around 1524, the majority of the Maya’s most important cities had already been abandoned. Meanwhile, the newly arrived Spanish explorers paid little attention to the ruins that lay scattered throughout their colonies, even as they seized Maya lands and forced its Indigenous people to convert to Christianity.</p>
<p><strong>The Maya in modern times</strong></p>
<p>It wasn’t until the 1840s that the Maya were “rediscovered” by explorers and researchers who were intrigued by the hints of the civilization they had left behind. American attorney and diplomat John Lloyd Stephens and English artist and architect Frederick Catherwood led a series of archaeological expeditions to Central America, where they mapped and documented Maya sites.</p>
<p>Though the existence of ruins in the area was known, many Europeans assumed that Indigenous Central Americans were primitive and unintelligent and had not created the historic artifacts beneath their feet. Stephens and Catherwood wanted to prove them wrong and establish both the worth of the sites and the identities of their creators. Despite being convinced of the former glory of the Maya, the two researchers also tried to profit from what they found, even attempting to purchase entire Maya cities and transport them to a New York museum. Nonetheless, their work forced the world to take notice of Maya civilization and lay a foundation for future archaeological discoveries.</p>
<p>Today, the field of Maya archaeology is flourishing, and present-day excavations have revealed everything from ruins to religious relics in the jungle that once reclaimed them. Scholars are still attempting to discover more about the Maya, their ambitious rise, and mysterious fall. While archaeological relics may be all that’s left of their past, the Maya still exist in the present. More than six million Maya descendants live in modern Central America, where more than 30 languages stemming from ancient Mayan are still spoken.</p>
<p>These descendants also keep many Mayan agricultural, religious, and land management traditions alive—a sign of the Mayan culture’s resilience in the face of centuries of challenge and change.</p>`
}
];

let questions = [
{p:0,type:"mc",std:"RL.8.2, RL.8.3",q:"Which statement best explains how Baltun’s internal conflict develops the theme of the legend?",opts:["His fear of being powerless causes him to confuse ownership with security, which shows that greed often grows from unresolved insecurity.","His desire to become the village leader proves that ambition is always more destructive than poverty.","His refusal to believe in the Aluxes shows that traditions are valuable only when supernatural beings prove they exist.","His childhood poverty explains why the villagers should forgive him before he repairs the harm he caused."],ans:[0],hint:"This stem asks how a character’s inner struggle develops a larger lesson. Look for the answer that connects motivation, change, and theme."},
{p:0,type:"multi",std:"RL.8.1, RL.8.2",q:"Select TWO pieces of evidence that most strongly support the theme that respect for the land requires restraint, not control.",opts:["“Because the land gives what it is ready to give. Taking too much brings imbalance.”","“Balance does not feed ambition.”","“Now I think strength means knowing what should never belong to you.”","“Corn grows from work, not from feeding invisible creatures.”","“Some villagers admired him for this.”"],ans:[0,2],hint:"For multiple-answer questions, every correct choice must support the same theme directly, not merely mention farming or ambition."},
{p:0,type:"mc",std:"RL.8.4",q:"In the sentence, “Jealousy began to grow inside him like a poison vine,” what is the effect of the figurative language?",opts:["It portrays jealousy as invasive and harmful, foreshadowing how Baltun’s envy will entangle his judgment.","It suggests Baltun has been physically poisoned by plants in Teyo’s field.","It emphasizes that jealousy is natural and therefore impossible for Baltun to resist.","It shows that Baltun’s envy will help him grow stronger like a vine climbing upward."],ans:[0],hint:"Interpret figurative language by asking what comparison is being made and what mood or foreshadowing it creates."},
{p:0,type:"drag",std:"RL.8.3, RL.8.5",q:"Drag each event into the correct narrative function.",items:["Teyo leaves offerings before planting","Baltun announces he will clear the sacred forest","Baltun meets the Alux leader at the ruins","Baltun replants trees and protects the temple"],zones:["Establishes Teyo’s values","Introduces the central conflict","Creates the turning point","Shows resolution through changed action"],ans:{"Establishes Teyo’s values":["Teyo leaves offerings before planting"],"Introduces the central conflict":["Baltun announces he will clear the sacred forest"],"Creates the turning point":["Baltun meets the Alux leader at the ruins"],"Shows resolution through changed action":["Baltun replants trees and protects the temple"]},hint:"Think about plot structure: setup, conflict, climax/turning point, and resolution."},
{p:0,type:"mc",std:"RL.8.6",q:"How does Nana Ixchel’s point of view influence the reader’s understanding of the conflict?",opts:["Her perspective frames the conflict as a spiritual and ethical violation rather than simply a disagreement about farmland.","Her perspective proves that the village elders are afraid of economic progress.","Her perspective makes Baltun seem completely evil and incapable of change.","Her perspective suggests Teyo’s farming success comes only from magic, not his careful choices."],ans:[0],hint:"Point of view questions ask how a speaker’s beliefs shape meaning, not just what the speaker says."},
{p:0,type:"mc",std:"RL.8.5",q:"Why does the author place Baltun’s explanation of his childhood poverty near the climax instead of at the beginning?",opts:["It complicates Baltun’s character at the moment of judgment, forcing readers to see his greed as rooted in fear rather than simple villainy.","It delays the exposition because the author forgot to explain Baltun’s background earlier.","It proves that Baltun’s actions were justified since he had suffered as a child.","It shifts the genre from legend to autobiography."],ans:[0],hint:"Structure questions often ask why information appears where it does. Consider how timing affects sympathy, tension, and complexity."},
{p:0,type:"multi",std:"RL.8.1, RL.8.3",q:"Select TWO details that reveal Baltun’s change is genuine rather than temporary.",opts:["He stopped the clearing.","He paid workers to replant the trees.","He awoke covered in leaves and dust.","He once swore he would never be powerless again.","He shouted that someone was playing tricks on him."],ans:[0,1],hint:"Choose actions after the turning point that demonstrate responsibility. Avoid details from before the change."},
{p:0,type:"mc",std:"RL.8.2, RL.8.6",q:"Which interpretation best explains the final statement, “The earth remembers how we treat it”?",opts:["Human actions toward nature and history carry lasting consequences, even when people try to ignore them.","The soil literally records every person’s footsteps and conversations.","The Aluxes punish every farmer equally regardless of behavior.","Ancient legends are more important than modern farming methods."],ans:[0],hint:"Interpret final lines as a theme statement. Avoid answers that are too literal or too extreme."},

{p:1,type:"mc",std:"RL.8.2, RL.8.6",q:"Which central idea is most strongly developed in the excerpt from the Popol Vuh?",opts:["Writing preserves cultural memory when oral teachers and sacred texts are threatened by disappearance.","The K’iche’ people rejected all religious traditions that came from outside their community.","Creation stories are valuable only when they explain scientific causes of the universe.","The speaker believes ancient words should remain hidden from future generations."],ans:[0],hint:"Look for repeated ideas. The speaker repeatedly emphasizes writing down ancient words because they may be lost."},
{p:1,type:"mc",std:"RL.8.4",q:"What does the phrase “root-place” most likely suggest about K’iche’?",opts:["It is a place of origin, identity, and cultural foundation.","It is a remote forest where roots physically cover the land.","It is a temporary settlement with little historical meaning.","It is a place disconnected from language and ancestry."],ans:[0],hint:"Use context. The phrase is connected to source, ancient words, and beginnings."},
{p:1,type:"multi",std:"RL.8.1, RL.8.5",q:"Select TWO lines or phrases that best show the speaker’s purpose for recording the text.",opts:["“we’re going to write down the ancient words”","“because there’s no longer / anywhere to find them”","“Great White Peccary, Wide-Eyed Coati”","“stretching the cord across the sky”","“anywhere there are skies”"],ans:[0,1],hint:"Purpose is about why the speaker is writing. Choose evidence about recording and preservation."},
{p:1,type:"mc",std:"RL.8.5",q:"How does the repeated phrase “we’re going to write” affect the structure of the excerpt?",opts:["It creates a ceremonial, urgent rhythm that emphasizes preservation as an intentional act.","It interrupts the excerpt with unrelated information about the author’s writing habits.","It makes the text sound casual and uncertain, weakening the sacred tone.","It proves the excerpt is organized as a modern research report."],ans:[0],hint:"Repetition can build rhythm, urgency, emphasis, and structure."},
{p:1,type:"drag",std:"RL.8.4, RL.8.6",q:"Drag each phrase to the meaning it most strongly conveys.",items:["Maker, Shaper","Heart of the Lake, Heart of the Sea","two times a midwife, two times a matchmaker","place of shadows"],zones:["Creative power","Sacred presence in nature","Birth and connection","Cultural loss or danger"],ans:{"Creative power":["Maker, Shaper"],"Sacred presence in nature":["Heart of the Lake, Heart of the Sea"],"Birth and connection":["two times a midwife, two times a matchmaker"],"Cultural loss or danger":["place of shadows"]},hint:"Use connotation. Match each phrase to the idea it symbolically suggests."},
{p:1,type:"mc",std:"RL.8.6",q:"Which statement best describes the speaker’s point of view toward Christianity spreading around them?",opts:["The speaker recognizes its presence as a pressure that makes preserving K’iche’ words more urgent.","The speaker celebrates Christianity as the only reason the ancient words survived.","The speaker ignores Christianity because it has no connection to cultural preservation.","The speaker presents Christianity as identical to the K’iche’ creation story."],ans:[0],hint:"The wording “even as” signals pressure or contrast. Think about how that pressure affects purpose."},
{p:1,type:"mc",std:"RL.8.2, RL.8.4",q:"What is the most likely meaning of “with the clarity of their words” in the context of creation?",opts:["Language is portrayed as powerful, purposeful, and capable of shaping existence.","The gods used simple language because they lacked complex ideas.","The speaker criticizes the creators for being too direct.","Words are shown as less important than physical labor."],ans:[0],hint:"In sacred texts, words may symbolize creation, order, authority, and memory."},
{p:1,type:"mc",std:"RL.8.5, RL.8.1",q:"Why does the excerpt list many names for the creators instead of using one simple title?",opts:["The list expands the creators’ significance by showing their many roles in nature, birth, protection, and existence.","The list suggests the speaker cannot remember the correct name of the creators.","The list is included only to confuse readers unfamiliar with K’iche’ language.","The list proves that the creators are ordinary animals rather than sacred beings."],ans:[0],hint:"When a text uses a long catalog/list, ask what the accumulation adds to meaning."},

{p:2,type:"mc",std:"RI.8.2",q:"Which central idea best captures the article as a whole?",opts:["Although much about the ancient Maya remains mysterious, evidence from archaeology and living descendants reveals a sophisticated and resilient civilization.","The Maya disappeared completely after their cities were abandoned and can now be studied only through ruins.","European explorers were the first people to understand and preserve Maya history accurately.","The Maya civilization is mainly important because its calendar predicted modern events."],ans:[0],hint:"Central idea must cover the whole article, including ancient achievements, mysteries, decline, and modern descendants."},
{p:2,type:"multi",std:"RI.8.1, RI.8.2",q:"Select TWO details that best support the idea that Maya civilization was sophisticated.",opts:["They laid foundations for trade routes, irrigation, water purification, writing, and a complex calendar.","They refined pyramid-like temples and grand buildings during the Classic period.","Most evidence was covered by vines and vegetation.","Some people abandoned cities and settled in small villages.","European explorers tried to purchase entire Maya cities."],ans:[0,1],hint:"Sophisticated means advanced or complex. Choose details showing achievements, not just discovery or decline."},
{p:2,type:"mc",std:"RI.8.3",q:"How did maize cultivation affect Maya society according to the article?",opts:["It helped shift Maya life toward permanent settlements and fueled the development of society and culture.","It caused the Maya to abandon all other crops and stop trading with neighbors.","It immediately ended the need for irrigation, water purification, and urban planning.","It made the Maya dependent on European farming methods."],ans:[0],hint:"Cause-and-effect questions require a clear relationship. Avoid choices that exaggerate or contradict the text."},
{p:2,type:"mc",std:"RI.8.4",q:"In the sentence, “city-states and local rulers vacillated between peaceful coexistence and wrestling for control,” what does “vacillated” most nearly mean?",opts:["shifted back and forth","permanently united","secretly disappeared","carefully measured"],ans:[0],hint:"Use the contrast between peaceful coexistence and wrestling for control."},
{p:2,type:"drag",std:"RI.8.5",q:"Drag each section idea to its function in the article’s structure.",items:["Explorers find ruins hidden in plain sight","Origins and maize cultivation are explained","Achievements such as cities, calendars, and architecture are described","Modern descendants keep traditions alive"],zones:["Hook / historical mystery","Background development","Evidence of complexity","Continuity and resilience"],ans:{"Hook / historical mystery":["Explorers find ruins hidden in plain sight"],"Background development":["Origins and maize cultivation are explained"],"Evidence of complexity":["Achievements such as cities, calendars, and architecture are described"],"Continuity and resilience":["Modern descendants keep traditions alive"]},hint:"Text structure questions ask what each section does for the reader."},
{p:2,type:"mc",std:"RI.8.6",q:"What is the author’s point of view toward the idea that the Maya simply “collapsed” or disappeared?",opts:["The author complicates that idea by explaining both urban decline and the continued survival of Maya people and traditions.","The author fully accepts the idea that the Maya vanished after the tenth century.","The author argues that the Maya had no descendants because only ruins remain.","The author avoids discussing decline because it is unrelated to Maya history."],ans:[0],hint:"Author’s point of view may be shown through what information is included and what misconception is corrected."},
{p:2,type:"mc",std:"RI.8.8",q:"Which statement best evaluates the article’s reasoning about the Maya’s decline?",opts:["The article presents decline as multi-causal and uncertain by naming warfare, trade decline, death rate, drought, and farming practices rather than a single simple cause.","The article proves drought was the only cause by rejecting all other explanations.","The article blames European explorers for the ninth- and tenth-century decline.","The article argues that the Long Count calendar caused people to abandon cities."],ans:[0],hint:"RI.8.8 asks you to evaluate argument/reasoning. Look for how the author supports a claim and avoids oversimplification."},
{p:2,type:"multi",std:"RI.8.1, RI.8.6",q:"Select TWO details that reveal the article challenges earlier European assumptions about Indigenous Central Americans.",opts:["Many Europeans assumed Indigenous Central Americans were primitive and unintelligent.","Stephens and Catherwood wanted to prove them wrong and establish the worth of the sites and identities of their creators.","The Long Count calendar began a new cycle on December 21, 2012.","Some northern cities continued to flourish.","The Maya worshiped their gods with a variety of rituals."],ans:[0,1],hint:"Choose evidence connected to European assumptions and the article’s correction of those assumptions."}
];

let order = [...Array(questions.length).keys()];
let current = 0, student="", answers={}, notes={};

function shuffle(arr){
  for(let i=arr.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1)); [arr[i],arr[j]]=[arr[j],arr[i]];}
  return arr;
}
function startGame(){
  student = document.getElementById("studentName").value.trim();
  if(!student){alert("Please enter your full name."); return;}
  questions.forEach((q,idx)=>{
    if(q.type==="mc"||q.type==="multi"){
      q.shuffled = shuffle(q.opts.map((text,i)=>({text,orig:i})));
    } else if(q.type==="drag"){
      q.shuffledItems = shuffle([...q.items]);
    }
  });
  document.getElementById("startScreen").classList.remove("active");
  document.getElementById("gameScreen").classList.add("active");
  document.getElementById("welcome").textContent = "Scholar: " + student;
  render();
}
function render(){
  const q = questions[order[current]];
  document.getElementById("passageBox").innerHTML = passages[q.p].html;
  document.getElementById("notes").value = notes[q.p] || "";
  document.getElementById("counter").textContent = `Question ${current+1} of ${questions.length}`;
  document.getElementById("progress").style.width = `${(current/questions.length)*100}%`;
  document.getElementById("warning").textContent = "";
  const box = document.getElementById("questionBox");
  let html = `<div class="qtitle">${current+1}. ${q.q}</div><div class="standards">Standards: ${q.std} | DOK 3–4</div>`;
  if(q.type==="mc"||q.type==="multi"){
    const inputType = q.type==="mc" ? "radio":"checkbox";
    q.shuffled.forEach((o,i)=>{
      const checked = (answers[current]||[]).includes(o.orig) ? "checked":"";
      html += `<label class="option"><input type="${inputType}" name="q${current}" value="${o.orig}" ${checked} onchange="saveChoice()">${String.fromCharCode(65+i)}. ${o.text}</label>`;
    });
  } else if(q.type==="drag"){
    html += `<div class="dragWrap"><div><h3>Choices</h3><div id="dragItems">`;
    let placed = answers[current] || {};
    let placedItems = Object.values(placed).flat();
    q.shuffledItems.filter(it=>!placedItems.includes(it)).forEach(it=> html += `<div class="dragItem" draggable="true" ondragstart="drag(event)" id="${safeId(it)}">${it}</div>`);
    html += `</div></div><div>`;
    q.zones.forEach(z=>{
      html += `<div class="dropZone" ondrop="drop(event,'${z.replace(/'/g,"\\'")}')" ondragover="allowDrop(event)"><h4>${z}</h4><div id="zone-${safeId(z)}">`;
      (placed[z]||[]).forEach(it=> html += `<div class="dragItem" draggable="true" ondragstart="drag(event)" id="${safeId(it)}">${it}</div>`);
      html += `</div></div><br>`;
    });
    html += `</div></div><button class="smallBtn" onclick="clearDrag()">Clear Drag Answers</button>`;
  }
  box.innerHTML = html;
}
function safeId(s){return "id_"+s.replace(/[^a-zA-Z0-9]/g,"_");}
function saveNotes(){ notes[questions[order[current]].p] = document.getElementById("notes").value; }
document.getElementById("notes").addEventListener("input", saveNotes);
function saveChoice(){
  const selected = [...document.querySelectorAll(`#questionBox input:checked`)].map(x=>Number(x.value));
  answers[current] = selected;
}
function allowDrop(ev){ev.preventDefault();}
function drag(ev){ev.dataTransfer.setData("text", ev.target.textContent);}
function drop(ev,zone){
  ev.preventDefault();
  let item = ev.dataTransfer.getData("text");
  if(!answers[current]) answers[current]={};
  Object.keys(answers[current]).forEach(z=>answers[current][z]=answers[current][z].filter(x=>x!==item));
  if(!answers[current][zone]) answers[current][zone]=[];
  answers[current][zone].push(item);
  render();
}
function clearDrag(){answers[current]={}; render();}
function answered(){
  const q=questions[order[current]], a=answers[current];
  if(q.type==="drag") return a && Object.values(a).flat().length===q.items.length;
  return Array.isArray(a) && a.length>0;
}
function nextQuestion(){
  saveNotes();
  if(!answered()){document.getElementById("warning").textContent="Please answer before moving forward."; return;}
  if(current<questions.length-1){current++; render(); window.scrollTo(0,0);}
}
function prevQuestion(){ saveNotes(); if(current>0){current--; render(); window.scrollTo(0,0);} }
function isCorrect(q,a){
  if(q.type==="mc"||q.type==="multi"){
    if(!Array.isArray(a)) return false;
    return q.ans.length===a.length && q.ans.every(x=>a.includes(x));
  }
  if(q.type==="drag"){
    if(!a) return false;
    for(const zone of Object.keys(q.ans)){
      const correct = q.ans[zone] || [];
      const got = a[zone] || [];
      if(correct.length!==got.length) return false;
      if(!correct.every(x=>got.includes(x))) return false;
    }
    return true;
  }
  return false;
}
function finishGame(){
  saveNotes();
  if(!answered()){document.getElementById("warning").textContent="Please answer before submitting."; return;}
  let missed=[], correct=0;
  questions.forEach((q,i)=>{
    if(isCorrect(q,answers[i])) correct++; else missed.push({num:i+1,q});
  });
  const score = Math.round((correct/questions.length)*100);
  document.getElementById("gameScreen").classList.remove("active");
  document.getElementById("resultScreen").classList.add("active");
  document.getElementById("finalScore").textContent = `${student}, your score is ${score}% (${correct}/${questions.length}).`;
  const cert = document.getElementById("certificate");
  if(score>=75){
    cert.innerHTML = `<div class="cert"><div class="badge">🏅</div><h1>Golden EOG Scholar Certificate</h1><h2>${student}</h2><p>has demonstrated strong analytical reading, evidence evaluation, and EOG readiness.</p><p class="scoreBig">${score}%</p><button class="mainBtn noPrint" onclick="window.print()">Print / Save Certificate</button></div>`;
  } else {
    cert.innerHTML = `<p class="warning">You are close. Review the missed question stems, reread the texts, and try again.</p>`;
  }
  const rev = document.getElementById("review");
  if(missed.length===0) rev.innerHTML = "<p>Excellent work. You did not miss any questions.</p>";
  else rev.innerHTML = missed.map(m=>`<div class="reviewItem"><strong>Question ${m.num}</strong><br>${m.q.q}<br><em>How to interpret this stem:</em> ${m.q.hint}</div>`).join("");
  window.scrollTo(0,0);
}
</script>
</body>
</html>

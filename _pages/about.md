---
permalink: /
title: "Home"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
body {
    min-height: 100vh;
    background-color: #fff;
}

.emoji {
    font-size: normal;
    min-width: 1.4em;
}

.emoji::after {
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}

.clock::after {
    content: '🕛';
    animation-name: clock;
    animation-duration: 5s;
}

.mailbox::after {
    content: '📪';
    animation-name: mailbox;
    animation-duration: 2.5s;
}

.camera::after {
    content: '📷';
    --emoji: '📸';
    animation-name: twoFrames;
    animation-duration: 1.2s;
}

.hourglass::after {
    content: '⏳';
    --emoji: '⌛️';
    animation-name: twoFrames;
    animation-duration: 1.2s;
}

.earth::after {
    content: '🌎';
    --emoji-1: '🌍';
    --emoji-2: '🌏';
    animation-name: threeFrames;
    animation-duration: 1.5s;
}

.moon::after {
    content: '🌕';
    animation-name: moon;
    animation-duration: 1s;
}

.bomb::after {
    content: '💣';
    --emoji: '💥';
    animation-name: twoFrames;
    animation-duration: 2s;
}

.monkey::after {
    content: '🙈';
    --emoji-1: '🙉';
    --emoji-2: '🙊';
    animation-name: threeFrames;
    animation-duration: 2s;
}

.hearts::after {
    content: '💗';
    animation-name: hearts;
    animation-duration: 3s;
}

.wave::after {
    content: '✋';
    --emoji: '👋';
    animation-name: twoFrames;
    animation-duration: 1s;
}

.inbox::after {
    content: '📥';
    --emoji: '📤';
    animation-name: twoFrames;
    animation-duration: 1s;
}

.vomit::after {
    content: '🤢';
    --emoji: '🤮';
    animation-name: twoFrames;
    animation-duration: 1s;
}

@keyframes twoFrames {
    50% {
        content: var(--emoji);
    }
}

@keyframes threeFrames {
    33.333% {
        content: var(--emoji-1);
    }

    66.666% {
        content: var(--emoji-2);
    }
}

@keyframes mailbox {
    25% {
        content: '📫';
    }

    50% {
        content: '📬';
    }

    75% {
        content: '📭';
    }
}

@keyframes hearts {
    16.666% {
        content: '🧡';
    }

    33.333% {
        content: '💛';
    }

    50% {
        content: '💚';
    }

    66.666% {
        content: '💙';
    }

    83.333% {
        content: '💜';
    }
}

@keyframes moon {
    12.5% {
        content: '🌖';
    }

    25% {
        content: '🌗';
    }

    37.5% {
        content: '🌘 ';
    }

    50% {
        content: '🌑';
    }

    62.5% {
        content: '🌒';
    }

    75% {
        content: '🌓';
    }

    87.5% {
        content: '🌔';
    }
}

@keyframes clock {
    8.333% {
        content: '🕐';
    }

    16.666% {
        content: '🕑';
    }

    25% {
        content: '🕒';
    }

    33.333% {
        content: '🕓';
    }

    41.666% {
        content: '🕔';
    }

    50% {
        content: '🕕';
    }

    58.333% {
        content: '🕖';
    }

    66.666% {
        content: '🕗';
    }

    75% {
        content: '🕘';
    }

    83.333% {
        content: '🕙';
    }

    91.666% {
        content: '🕚';
    }
}
</style>
<style>
        /* Basic CSS for layout */
        .container {
            display: grid;
            grid-template-columns: 5fr 1fr;
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .content {
            font-size: 0.875em;
        }

        .news {
            margin-right: -220px;
            border-left: 2px solid #ccc;
            /* line-height: 450px; */
            padding-left: 20px;
            font-size: 0.8em;
            height: 450px; /* Adjust height as needed */
        }

        .news-content {
            max-height: 350px; /* Set the scrollable height */
            overflow-y: auto; /* Enable vertical scrolling */
            padding-right: 10px;
        }

        .emoji {
            display: inline-block;
        }
</style>
<div class="container">
        <div class="content">
        Hello! <span class="emoji wave" role="img" aria-label="hand wave"></span><br>
        I am Syed Rifat Raiyan.
        <div id="pronounceLink" style="display:block;"><p><a href="#" onclick="$('#pronounce').toggle(); return false;"><i>How to pronounce?</i></a></p></div>
        <div id="pronounce" style="display: none;" class="alert">
            <p>Here is a standard Bangla pronunciation:<br>
                <audio controls="">
                    <source src="audio/Syed-Rifat-Raiyan.mp3" type="audio/mpeg">
                </audio>
            </p>
        </div>
        I am a Lecturer of the Department of Computer Science and Engineering (CSE) at the Islamic University of Technology (IUT). In May of 2023, I attained my Bachelor of Science (B.Sc.) degree with Honors from the Department of Computer Science and Engineering (CSE) at the Islamic University of Technology (IUT). I was affiliated with the <a href="https://cse.iutoic-dhaka.edu/ssl">Systems and Software Lab (SSL)</a> research group of IUT while I was working on my undergraduate thesis under the supervision of <a href="https://cse.iutoic-dhaka.edu/profile/mohsinul/education">Mohsinul Kabir</a>.
<!-- <br> -->
        <br>
        <br>
        My research interests lie broadly in Natural Language Processing, Computer Vision, and Deep Learning. These days, I am working on projects related to Mathematical Reasoning in Language Models, In-context Learning for Text Classification, Bangla Sentiment Analysis, and Image Classification.
<!-- <br> -->
        <br>
        <br>
        Some people in academia that I follow/look up to — 
<br>
        <a href="https://karpathy.ai/">Andrej Karpathy</a>, <a href="https://www.andrewng.org/">Andrew Ng</a>, <a href="https://autarkaw.com">Autar Kaw</a>, <a href="https://en.wikipedia.org/wiki/Bret_Weinstein">Bret Weinstein</a>, <a href="https://nlp.stanford.edu/~manning/">Christopher D. Manning</a>, <a href="https://www.cs.princeton.edu/~danqic/">Danqi Chen</a>, <a href="https://cs.harvard.edu/malan/">David J. Malan</a>, <a href="https://www-cs-faculty.stanford.edu/~knuth/">Donald E. Knuth</a>, <a href="http://erikdemaine.org/">Erik Demaine</a>, <a href="https://math.mit.edu/~gs/">Gilbert Strang</a>, <a href="https://www.3blue1brown.com/">Grant Sanderson</a>, <a href="http://www-formal.stanford.edu/jmc/index.html">John McCarthy</a>, <a href="https://jonathanhaidt.com/">Jonathan Haidt</a>, <a href="https://www.jordanbpeterson.com/">Jordan B Peterson</a>, <a href="https://web.eecs.umich.edu/~justincj/">Justin Johnson</a>, <a href="https://scholar.google.com/citations?user=WgyrxUAAAAAJ&hl=en">Károly Zsolnai-Fehér</a>, <a href="https://www.math.mcgill.ca/lnchen/">Linan Chen</a>, <a href="https://chomsky.info/">Noam Chomsky</a>, <a href="https://web.archive.org/web/20230808013415/https://rebeccashafee.com/index.html">Rebecca Shafee</a>, <a href="https://en.wikipedia.org/wiki/Roger_Penrose">Roger Penrose</a>, <a href="https://people.csail.mit.edu/devadas/">Srinivas Devadas</a>, <a href="https://www.math.ucla.edu/~tao/">Terence Tao</a>.
</div>
<div class="news">
    <h2><img src="https://raw.githubusercontent.com/Starscream-11813/Starscream-11813.github.io/refs/heads/master/images/quill-pen-cropped.svg" style="width: 25px; vertical-align: bottom">Chronicle</h2>
    <div class="news-content">
        <b>17th July 2024:</b> Submitted my CSE 4836 project's paper to <a href="https://cis.ieee.org/publications/ieee-transactions-on-artificial-intelligence">IEEE TAI</a>. Preprint is available at <a href="https://www.arxiv.org/abs/2408.10360">arXiv</a>. Let's hope for the best!
        <br>
        <br>
        <b>2nd February 2024:</b> Became a reviewer at <a href="https://link.springer.com/journal/42979">Springer Nature Computer Science</a>.
        <br>
        <br>
        <b>16th August 2023:</b> Got my first-ever job — Lecturer at <a href="https://cse.iutoic-dhaka.edu/">IUT CSE</a>.
        <br>
        <br>
        <b>9th July 2023:</b> Virtually presented a poster of my B.Sc. thesis work at ACL 2023.
        <br>
        <br>
        <b>8th June 2023:</b> My B.Sc. thesis work on MWPs got accepted for publication in <a href="https://aclanthology.org/2023.acl-srw.49/">ACL-SRW 2023</a>. Alhamdulillah!
        <br>
        <br>
        <b>2nd May 2023:</b> My first-ever paper got accepted for publication in the <a href="https://aclanthology.org/2023.findings-acl.80/">Findings of ACL 2023</a>. Alhamdulillah!
    </div>
</div>
</div>
<br>
<div style="float: right;">
    <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=500&t=tt&d=w_TeJiwbvCfFyZ0dPOrLIdVwWFumXWn3fCcf3Egyhho&co=71addc&cmo=deac7c&cmn=b4d27c&ct=ffffff'></script>
</div>
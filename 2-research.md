---
layout: page
title: Research
permalink: /research/
---

<style>
 
 html * {
        font-family: Cambria,Georgia,serif; 
      }
   
   .iframe-container {
  padding-top: 56.25%;
  position: relative;
   }

.iframe-container iframe {
   border: 0;
   height: 100%;
   width: 100%;
   position: absolute;
   top: 0;
   left: 0;
 }
   
  .button {
     border: none;
     color: white;
     padding: 8px 32px;
     text-align: center;
     text-decoration: none;
     display: inline-block;
     font-size: 16px;
     margin: 0px 0px;
     transition-duration: 0.4s;
     cursor: pointer;
}
   
 .button-1 {
  background-color: #FFFFFF;
  border: 0;
  border-radius: .5rem;
  box-sizing: border-box;
  /*color: #1f4071;*/
  color: #86152c;
  font-family: Cambria,Georgia,serif; 
  font-size: .75rem;
  font-weight: 600;
  line-height: 1rem;
  padding: .2rem .75rem;
  text-align: center;
  text-decoration: none #D1D5DB solid;
  text-decoration-thickness: auto;
  box-shadow: 0 3px 9px 0 rgba(0, 0, 0, 0.1), 0 3px 6px 3px rgba(0, 0, 0, 0.06);
  transition-duration: 0.4s;
  margin: 0px 0px;
  cursor: pointer;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  white-space: nowrap;
}

.button-1:hover {
  /* background-color: rgb(31, 64, 113);*/
  background-color: rgb(134, 21, 44);
  color: white;
}

.button-1:focus {
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.button-1:focus-visible {
  box-shadow: none;
}
   
 .collapse{
  display:none
}

.collapse.in{
    display:block
  }

tr.collapse.in{
  display:table-row
}

tbody.collapse.in{
  display:table-row-group
}

.collapsing{
  position:relative;
  height:0;
  overflow:hidden;
  -webkit-transition-property:height,visibility;
  -o-transition-property:height,visibility;
  transition-property:height,visibility;
  -webkit-transition-duration:.35s;
  -o-transition-duration:.35s;
  transition-duration:.35s;
  -webkit-transition-timing-function:ease;
  -o-transition-timing-function:ease;
  transition-timing-function:ease
}
   
 p.ex1 {
  padding-top: 0em;
  padding-bottom: 0em;
  font-size:14px;
}
   
 a:link, a:visited {
  background-color: white;
  color: rgb(134, 21, 44);
  text-align: center;
  text-decoration: none;
  white-space: nowrap;
}
 
 a:hover {
   text-decoration:underline;
}
 
 .last-line {
    display: block;
    margin-left: 0px; 
}

.citation-popup {
    display: none;
    position: fixed;
    z-index: 1;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgba(0, 0, 0, 0.4);
}

.citation-content {
    position: relative;
    background-color: #fefefe;
    margin: 10% auto;
    padding: 20px;
    width: 60%;
    border-radius: 10px; 
    overflow: auto;
}

.close {
    color: #aaaaaa;
    position: absolute;
    top: 10px; 
    right: 10px; 
    font-size: 24px;
    font-weight: bold;
    cursor: pointer;
    padding: 0 10px;
}
 
 table tr:not(:last-child) {
    margin-bottom: 5px;
    padding-bottom: 5px;
}

table td {
    padding: 10px 30px; 
    text-indent: -30px;
}
 

 table td:last-child {
    text-indent: 0px;
    text-align: center;
}


.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
 
    
 </style>



### Job Market Paper

<p class="ex1" align="justify"> <b>JMP title</b> <br>
<a class="button-1" role="button" href="/files/jmp.pdf" target="_blank" style="line-height:35px; text-decoration: none">Working Paper <i class="fa fa-file-pdf-o"></i></a>
 
<a class="button-1" role="button" data-toggle="collapse" data-target="#abs1" style="line-height:35px; text-decoration: none">Abstract +</a>
 
  <div id="abs1" class="collapse">
    <div style="padding-left: 30px;">
   <p style="font-size:13px" align="justify"> Details of the abstract here!.</p>
  </div>
 </div>


### Working Papers

<p class="ex1" align="justify"> <b>Paper Title </b> (with <a href="https://davidalbouy.com/" target="_blank"> David Albouy</a> , <a href="https://sites.google.com/site/gabrielehrlich/home" target="_blank">Gabriel Ehrlich</a> and <a href="" target="_blank">Yingyi Liu</a>)
 
<p class="ex1" align="justify"> <b>Paper Title </b>  (with <a href="https://sites.google.com/site/markborgschulte/" target="_blank"> Mark Borgschulte</a> and <a href="https://www.rebeccathornton.net/" target="_blank"> Rebecca Thornton </a>) </p>
 
### Selected Work in Progress

<p class="ex1" align="justify"> <b>Municipal Annexations: Determinants and Consequences</b> </p>
 
 <p class="ex1" align="justify"> <b> Paper 3 </b> </p> (with <a href="https://sites.google.com/site/markborgschulte/" target="_blank"> Mark Borgschulte</a> and <a href="" target="_blank"> Rebecca Thornton </a>) </p>


### Referred Publications

<p class="ex1" align="justify"> 
   <b> Assessing the linkage between dairy productivity growth and climatic variability: The case of New York State </b> (with <a href="https://home.iitk.ac.in/~deepm/" target="_blank">Deep Mukherjee</a>) <br> <em>Open Agriculture</em>, 2018. <br>
   <a class="button-1" role="button" href="" target="_blank" style="line-height:35px; text-decoration: none"> <i class="fa fa-file-pdf-o"></i></a> </p>
   
   
   
   
<script>
  document.getElementById('citeButton').addEventListener('click', function () {
      document.getElementById('citationPopup').style.display = 'block';
  });

  document.querySelector('.close').addEventListener('click', function () {
      document.getElementById('citationPopup').style.display = 'none';
  });

  window.addEventListener('click', function (event) {
      if (event.target == document.getElementById('citationPopup')) {
          document.getElementById('citationPopup').style.display = 'none';
      }
  });

  function copyCitation(citationId, messageId) {
      const citationText = document.getElementById(citationId);
      const textarea = document.createElement('textarea');
      textarea.textContent = citationText.textContent;
      textarea.style.position = 'fixed';
      document.body.appendChild(textarea);
      textarea.select();
      try {
          document.execCommand('copy');
          showCopyMessage(messageId);
      } catch (err) {
          console.warn('Copy failed:', err);
      } finally {
          document.body.removeChild(textarea);
      }
  }

  function showCopyMessage(messageId) {
      const copyMessage = document.getElementById(messageId);
      copyMessage.style.display = 'inline';
      copyMessage.textContent = 'Citation copied to clipboard';
      setTimeout(() => {
          copyMessage.style.display = 'none';
      }, 1000);
  }

  document.getElementById('copyIcon1').addEventListener('click', function () {
      copyCitation('citationText1', 'copyMessage');
  });

  document.getElementById('copyIcon2').addEventListener('click', function () {
      copyCitation('citationText2', 'copyMessage');
  });
</script>

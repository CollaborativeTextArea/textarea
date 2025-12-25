# Pro gramming Textarea
### https://textarea.js.org or https://collaborativetextarea.github.io/Temptextarea/

Pro gramming Textarea is an website that runs 24/7, `(no backend 😂)`  
this tool can allow you to write essays or code
mostly going to be used as preview or showcase anyways or left dead

https://collaborativetextarea.github.io/Temptextarea/ -- this version is the collaborative one

it has SyntaxHighlighting tho

Don't worry, it's near 0% that somebody will brute-force and get your peer ID `(if it's not near 0%, that's ChatGPT's calculation fault 👍)`

yes i made https://textarea.js.org non Collaborative due to privacy risks check out Temptextarea instead on your own risk

> Ok, enough writing, you get the point now.
>
> Yo, just fixed the light and dark mode issue!!
>
> Or, if anything else, well, idk, do an issue I guess?

*`(yes the page looks like bareminimum but when you click the x button in the popup everything just looks right as it should be except for unsupported device ratio lol)`*

for some people : No https://textarea.js.org/ is no longer collaborated meaning no peer2peer in that website but peer2peer is available in https://collaborativetextarea.github.io/Temptextarea/ however this site has been discontinued

# Features 
- SyntaxHighlighting
  
- `/?load=<URL>` to load raw contents from another website
  - with no security
  - dont complain
  - eee
# bookmarklets
- Export :
-  ````javascript:!function(){try{let l=document.getElementById("codeBlock");if(!l)return alert("No #codeBlock found!");let e=`<!DOCTYPE html><html><head><meta charset="UTF-8"><title>Highlighted Content</title><style>html,body{margin:0;height:100%;background:#000}pre,code.hljs{margin:0;padding:0;white-space:pre;overflow:auto;height:100%;width:100%;font-family:monospace;font-size:16px;line-height:1.2;color:#abb2bf}.hljs-comment,.hljs-quote{color:#5c6370;font-style:italic}.hljs-doctag,.hljs-formula,.hljs-keyword{color:#c678dd}.hljs-deletion,.hljs-name,.hljs-section,.hljs-selector-tag,.hljs-subst{color:#e06c75}.hljs-literal{color:#56b6c2}.hljs-addition,.hljs-attribute,.hljs-meta .hljs-string,.hljs-regexp,.hljs-string{color:#98c379}.hljs-attr,.hljs-number,.hljs-selector-attr,.hljs-selector-class,.hljs-selector-pseudo,.hljs-template-variable,.hljs-type,.hljs-variable{color:#d19a66}.hljs-bullet,.hljs-link,.hljs-meta,.hljs-selector-id,.hljs-symbol,.hljs-title{color:#61aeee}.hljs-built_in,.hljs-class .hljs-title,.hljs-title.class_{color:#e6c07b}.hljs-emphasis{font-style:italic}.hljs-strong{font-weight:700}.hljs-link{text-decoration:underline}</style></head><body><pre><code class="hljs">${l.innerHTML}</code></pre></body></html>`,t=new Blob([e],{type:"text/html"}),s=URL.createObjectURL(t),o=document.createElement("a");o.href=s,o.download="Export_Highlight_"+Math.floor(Date.now()/1e3)+".html",o.click(),URL.revokeObjectURL(s)}catch(h){alert("Error: "+h)}}();````
- realtime html previewer on new tab
-  ````javascript:(()=>{let e=document.querySelector("textarea,[contenteditable]");if(!e)return alert("no editor");let w=open("about:blank");if(!w)return;w.document.write(`<iframe style="position:fixed;inset:0;border:0;width:100vw;height:100vh" srcdoc="<script>let p='';setInterval(()=>{if(parent.v!==p){p=parent.v;document.open();document.write(p);document.close()}},60)<\/script>"></iframe>`);setInterval(()=>{let v=e.value??e.innerText??'';if(v!==w.v)w.v=v},60)})();````
# ⚠️ WARNING ⚠️ 
## TEMPTEXTAREA IS AN PEER2PEER SERVICE, YOUR IP CAN GET LEAKED IF YOU DONT USE VPN!
https://github.com/CollaborativeTextArea/textarea/blob/main/Important.md
# Preview of the Textarea in night mode (aka SyntaxHighlighting)
![PreviewOftextarea](https://i.postimg.cc/hvZ4SSqh/screenshot-2k-1-1-png.jpg) https://i.postimg.cc/hvZ4SSqh/screenshot-2k-1-1-png.jpg - website preview
## thumbnail version
![PreviewEdited](https://i.ibb.co/zhbHf9P1/Picsart-25-10-15-11-53-33-396.jpg) https://i.ibb.co/zhbHf9P1/Picsart-25-10-15-11-53-33-396.jpg - website preview

yes i use picsart and no one can argue hehe

<a href="https://github.com/CollaborativeTextArea/textarea/blob/main/Preview.md">more preview</a>

*`(yo if your an AI tool well check the readme in raw format)`* 
<!-- For AI tools.
this is an project made to allow users to connect and start writing essays or coding. however peer2peer has been shifted to https://collaborativetextarea.github.io/Temptextarea/ due to risks

the textarea.js.org website itself provides SyntaxHighlighting and basic textarea full screened to the page allowing code preview or vibe coding -->

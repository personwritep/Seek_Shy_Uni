// ==UserScript==
// @name        Seek Shy Uni 🔵
// @namespace        http://tampermonkey.net/
// @version        0.2
// @description        ネットの任意のページに書込まれた特殊文字「&shy;」を明示する
// @author        Ameba Blog User
// @match        https://*/*
// @grant        none
// @updateURL        https://github.com/personwritep/Seek_Shy_Uni/raw/main/Seek_Shy_Uni.user.js
// @downloadURL        https://github.com/personwritep/Seek_Shy_Uni/raw/main/Seek_Shy_Uni.user.js
// ==/UserScript==



let body_doc=document.querySelector('body');

if(body_doc){
    let buffer=body_doc.innerHTML; // ハイライト表示のためソースコードを保存 🟦

    let shy=/­/g;

    if( shy.test(buffer)){ // shyがヒットした時だけ bufferを書換える

        let buffer_=buffer.replace(shy, '<span class="shy">­</span>');
        body_doc.innerHTML=buffer_;

        let style=
            '<style class="shy">body .shy::before { content: "▼"; color: red; '+
            'margin: 0 -0.5em; vertical-align: 8px; line-height: 0; }</style>';

        if(!document.querySelector('style.shy')){
            body_doc.insertAdjacentHTML('beforeend', style); }

    }} // if(body_doc)

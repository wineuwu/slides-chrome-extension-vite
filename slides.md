---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: "#FFF"
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
colorSchema: "light"
drawings:
  persist: false
# page transition
transition: slide-left
fonts:
  sans: "Roboto"
# use UnoCSS
css: unocss
---

<div class="mx-auto w-full top-30 right-0 left-0 w-310px absolute">
<h1 class="font-bold mb-[40px] py-8 text-[#F0822A] text-2xl
"> 用 <span class=" bg-[#4F74AE] text-white  py-.5 px-2 inline-block ">Vite</span> 開啟你的 <span class=" bg-[#4F74AE] text-white mb-6  py-.5 px-2 inline-block ">Extension</span></h1>

<p class="text-base">套件用的好，讓你沒煩惱 | <s>套件，讓你與昨天說再見</s> </p>
</div>
<div class="mx-auto right-0 bottom-5 left-0 w-310px absolute">
  <span class=" w-310px inline-block">
    <img src ="/winnieXweblearn.png"/>
  </span>
</div>

---

  <h2 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-9 left-7.5 w-2 h-[40px] absolute bg-[#F0822A] mb-10"> 什麼是 Chrome Extension ? </h2>
  <div class="flex my-8 justify-center">
    <div class="mr-2 w-[210px]" >
      <img src="/1111.png" alt="" class="mt-30px w-full"/>
    </div>
    <div class="mt-5 w-[160px]" >
      <img src="/puzzle.png" alt="" class="mt-[20px] w-full"/>
    </div>
  </div>    
  <div class="px-5 bottom-20 text-[#696969] text-[18px] leading-7 absolute">
   <span class="tracking-normal"> Chrome Extension </span>為 <span class=" tracking-normal"> Chrome</span> 瀏覽器所提供的擴充工具，它能夠保持原始網站運作的狀態下，讓使用者可以透過瀏覽器所提供的權限來額外自定義附加功能，<span class="font-bold text-[#F0822A]">『 改變特定網站的外觀或者增加新的功能 』</span>，主要使用 <span class="font-bold tracking-normal text-[#F0822A]">『 HTML、CSS、JavaScript 』</span>來開發。
  </div>

---

<div class="flex h-full item-center">
<h2 class="font-bold my-auto  mx-auto bg-[#F0822A] text-white text-xl text-center p-3">以 Vue DevTool 為例</h2>
</div>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">以 Vue DevTool 為例</h3>
<div class="flex h-full space-x-6 mt-10  justify-center" v-click="1">
  <div class="text-center w-[400px]">
    <img src="/ext_react.jpg" alt=""/>
  </div>
  <div class="text-center w-[400px]">
    <img src="/ext_vue.jpg" alt="" />
  </div>
</div>
<div class="text-center px-5 bottom-20 text-[#696969] text-[17px] leading-7 absolute" v-click="1">
  Vue DevTool 會偵測當時網站有無使用 Vue 技術，如果該網站未使用到Vue開發，圖示呈現灰色狀態來表示<br/>反之，有使用到則呈現原本的顏色。
</div>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">以 Vue DevTool 為例</h3>
<div class="flex h-full  mt-2  justify-center" >
  <div class="w-[650px]">
    <img src="/devTool.png" alt="" />
  </div>
</div>

---

<div class="flex h-full item-center">
<h2 class="font-bold my-auto  mx-auto bg-[#F0822A] text-white text-xl text-center p-3"> 組成 與 運行環境 </h2>
</div>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">Chrome Extension 的 常見組成 </h3>

<div class="border-dashed mx-auto border-2 border-[#F9BA62] h-65%  px-5 pb-5  relative">
 <div class="mt-4 text-left mb-10px text-[#fca12a] text-22px" >
   Manifest
 </div>
 <div class="flex">      
    <div class="h-full text-[16px] w-1/2 ">
        <div class="bg-[#EDEDED] border-b border-dashed border-[#c6c6c6] h-1/3 text-center text-[#afaeae] transition-all leading-18.5 hover:border-none hover:bg-[#F0822A]  hover:text-white hover:scale-105">Action</div>
        <div class=" bg-[#EDEDED] border-dashed border-b border-[#c6c6c6] h-1/3 text-center text-[#afaeae] transition-all leading-18.5 hover:border-none hover:bg-[#F0822A] hover:text-white  hover:scale-105 ">Option</div>
        <div class=" bg-[#EDEDED] border-[#c6c6c6] h-1/3 text-center text-[#afaeae]  transition-all leading-18.5   hover:bg-[#F0822A]  hover:text-white hover:scale-105">Content Script(執行於 瀏覽器端)</div>
    </div>
    <div class="bg-[#EDEDED] border-l border-dashed border-[#c6c6c6] h-[223px] text-white text-center text-[#afaeae] transition-all  leading-[223px] w-1/2 hover:border-none hover:bg-[#F0822A] hover:text-white  hover:scale-105" >Background (service worker)</div>
 </div> 
</div>

<div class="mt-4 text-center  px-5 text-[#696969] text-[17px] leading-7" >
在 Extension 中 主要是由一個 Manifest 組成，而其他的權限功能 Content Script 、 Action 及 Option 等<br/>則視需要可在 Manifest.json 自定義
</div>

---

<h3 class="font-bold text-xl mb-5 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">運行環境</h3>

<div class="mt-2 text-center  px-5 text-[#696969] text-[17px] leading-7" >
運行環境可以分為兩個為完全獨立空間，分別是 <span class="font-bold text-[#F0822A]">Extension端 及 瀏覽器端</span>。因為是兩個互不影響，不能直接操作對方的相關方法，唯一溝通的方式只有透過<span class="font-bold text-[#F0822A]"> onMessage 事件監聽方法</span> 來進行雙方資料溝通。
</div>

 <div class="mx-auto mt-15px text-left w-[600px]" >
  <img src ="/operation.png"/>
 </div>

<div class="mt-4 text-center  px-5 text-[#696969] text-[17px] leading-7" >
</div>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">關於 Manifest</h3>

<div class="flex  space-x-12 mt-30 w-full justify-center ">
   
  <div un-after="content-none w-40 h-40 border-3 border-[#FA9949] rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FA9949] h-34 text-center  text-[#f9f7e8] leading-34 w-34 relative  "> Manifest </div>
  <div class="rounded-full bg-[#FDE5C4] bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" >  Background </div>
  <div class="rounded-full bg-[#FDE5C4] bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" > Action </div>
  <div class="rounded-full bg-[#FDE5C4]  bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" > Content Script </div>
</div>

<div class="mt-15 text-center  px-5 text-[#696969] text-[17px] leading-7" >
Manifest 為 套件主要程式設定檔，如基本名稱、版本、描述、各項權限都在此檔設定，所有功能的執行進入點
</div>

---

<h3 class="font-bold text-xl mb-5 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">Manifest 必填及建議項目</h3>

<div class=" mb-4  text-[#696969] relative">必填項目</div>

```json
{
  "name": "Extension DEMO ",
  "version": "1",
  "manifest_version": 3
  //...略
}
```

<div class=" my-4  text-[#696969] relative">建議項目</div>
```json
{
  "description": "DEMO Description",  // 建議
  "icons": {...},  // 建議
}
```

---

<h3 class="font-bold text-xl mb-2 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">Manifest 選填項目 </h3>

<div class="space-y-2 mt-10">
<div class="font-bold   pl-6 text-[18px] text-[#696969] relative"  un-after="block content-none rounded-full left-0 w-2 h-2 absolute bg-[#696969] top-0 bottom-0 my-auto "> permissions </div>

<span class="py-4 pl-6 text-[15px] text-[#696969] inline-block">
當 Extension 需要對瀏覽器 進行附加功能時，有可能會需要使用到 Browser 的功能(像是Cookie、Storage)協助，此時就需透過在 Permission 中進行使用宣告，才能進行 權限的使用。
</span>

```json
{
    permissions": [
    "storage",
    "activeTab", //目前視窗頁
    "tabs",
    "cookies" // 網站的cookie
  ],
}
```

</div>

<span class="bg-[#FDEEECCC] rounded-sm w-full p-4 text-[13px] text-[#EC5446] inline-block"> \* 提醒: 建議沒有使用到的權限記得就不要宣告，要不然會導致最後 google 送審 時會未能通過</span>

---

<h3 class="font-bold text-xl mb-2 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">Manifest 選填項目 </h3>

<div class="space-y-3 mt-10">
  <div class="font-bold  pl-6 text-[18px] text-[#696969] relative"  un-after="block content-none rounded-full left-0 w-2 h-2 absolute bg-[#696969] top-0 bottom-0 my-auto "> host_permissions </div>

  <span class="py-2 pl-6 text-[15px] text-[#696969] inline-block">
  主要使用時機為需在 Extension 中 Cross-origin 請求對應API資料時，需在 host_permissions 內定義相關網域的網址。
  </span>

```json
{
  "host_permissions": [
    "https://www.google.com/", // 指定特定連結
    "https://www.google.com/*", // 指定在特定網域下所有連結
    "<all_urls>" //所有都可以使用
  ]
}
```

</div>

<span class="rounded-sm text-right w-full p-2 text-[13px] text-[#A3A3A3] inline-block"> 更多 Manifest 相關功能設定 請見 -> <a href="https://developer.chrome.com/docs/extensions/mv3/match_patterns/" >官方文件</a></span>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">Chrome Extension 的 常見組成 Background</h3>

<div class="flex  space-x-12 mt-30 w-full justify-center ">
   
  <div class="rounded-full bg-[#FDE5C4] bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" >  Manifest </div>
  <div un-after="content-none w-40 h-40 border-3 border-[#FA9949] rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FA9949] h-34 text-center  text-[#f9f7e8] leading-34 w-34 relative  "> Background </div>
  <div class="rounded-full bg-[#FDE5C4] bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" > Action </div>
  <div class="rounded-full bg-[#FDE5C4]  bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" > Content Script </div>
</div>

<div class="mt-15 text-center  px-5 text-[#696969] text-[16px] leading-7" >
Background 為 Extension 中的 長時間執行腳本事件，通常 Extension 的相關的邏輯功能都會此進行定義，而其常見的功能主要為 <span class="text-[#F0822A]">監聽各項事件的發生、使『瀏覽器端』與『 Extension端 』進行資料溝通 及 跨域請求API資料 </span> 等...
</div>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-1.5 h-[30px] absolute bg-[#F0822A] mb-10">Chrome Extension 的 常見組成 Background</h3>

<div class="space-y-3 mt-10">

<div class="mt-15  mb-5 text-[#696969] text-[16px] leading-7" >
在 Manifest 3 中， Background 採用 <span class="text-[#F0822A]">Service Worker</span> 來運行，如果需使用 background 相關功能，首先需在 Manifest 內 background 欄位中指定檔案路徑，使用<span class="text-[#F0822A]"> ES Module </span> 只要 <span class="text-[#F0822A]">type 為 module</span> 即可使用。
</div>
  
```json
// manifest.json
{
  ...
  "background": {
    "service_worker": "background.js",
    "type": "module" //optional
  }
  ...
}
```
</div>

---

<h3 class="flex  font-bold m-auto  text-white text-left text-[#FA9949] items-center"><span class=" mr-4  text-[34px] block">🧀️</span> <span class="   block">什麼是 Service Worker ? </span></h3>

<div class="my-8  text-[17px] text-[#696969] leading-8 relative">
為瀏覽器與網路之間的一種網路請求代理(Proxy)，為PWA核心技術之一，主要特性為 <span class="text-[#FA9949]">無法存取DOM元素</span>，需透過 <span class="text-[#FA9949]">postMessage 方法</span>與其他溝通 、 主要透過<span class="text-[#FA9949]"> 事件監聽 </span>觸發每個生命週期 及 <span class="text-[#FA9949]">需在 HTTPS 下執行</span>，進行攔截請求
</div>

<div class="flex mt-20  justify-center items-center">
  <div v-click='1' un-after="content-none w-40 h-40 border-3 border-[#FA9949] rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FA9949] h-34 text-center  mr-14 text-[#f9f7e8] leading-34 w-34  relative"> 離線快取功能 </div>
  <div v-click='2' un-after="content-none w-40 h-40 border-3 border-[#FA9949] rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FA9949] h-34 text-center mr-14 text-[#f9f7e8] leading-34 w-34 relative  "> 推播通知功能 </div>
  <div v-click='3' un-after="content-none w-40 h-40 border-3 border-[#FA9949] rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FA9949] h-34 text-center  text-[#f9f7e8] leading-34 w-34 relative  "> 網站安全功能 </div>
</div>

---

<h3 class="flex  font-bold m-auto  text-white text-left text-[#FA9949] items-center"><span class=" mr-4  text-[34px] block">🧀️</span> <span class="   block">Service Worker 生命週期  </span></h3>

<div class="mx-auto mt-10 w-[650px]">
  <img src="https://i.imgur.com/v6ouFlq.png" alt="" class="mt-[20px] w-full"/>
</div>

---

<div class="flex h-full item-center">
<h3 class="font-bold my-auto  mx-auto bg-[#FA9949] text-white text-xl text-center p-3"> 關於 常見 事件 及 Chrome API </h3>
</div>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-1.5 h-[30px] absolute bg-[#F0822A] mb-10">Background 常見監聽事件</h3>

<div class="mt-15 mb-4   text-[16px] text-[#696969] relative"> 『 chrome.runtime.onInstalled 』  為 Extension 第一次被安裝時，執行事件的觸發，永遠只會觸發一次 </div>

```javascript
// background.js
const setStorage = (obj) => {
  chrome.storage.sync.set(obj, () => {});
};

chrome.runtime.onInstalled.addListener(async () => {
  console.log("Extension is Installed");
  //初始化資料
  await setStorage({
    isClear: false,
  });
});
```

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-1.5 h-[30px] absolute bg-[#F0822A] mb-10">Tab 頁籤 API及監聽事件</h3>

<div class="mt-8 mb-4   text-[16px] text-[#696969] relative"> 使用chrome.tabs API 可以與Browser的特定頁籤進行互動。像是創建、修改和重新排列頁籤順序等...</div>

```javascript
    // 創建新Tab
    chrome.tabs.create({ url: 'page.html' });

    // 取出目前Tab
   const getCurrentTab =()=>{
   let queryOptions = { active:true,
     lastFocusedWindow: true };
      let [tab] = await chrome.tabs.query(queryOptions);
      return tab;
    }

    //已開啟tab切換時觸發
    chrome.tabs.onActivated.addListener((tabId, windowId) => {});

    //當tab更新時觸發
    chrome.tabs.onUpdated.addListener((id, info, tab) => {});


```

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-1.5 h-[30px] absolute bg-[#F0822A] mb-10">Storage API及監聽事件</h3>
<div class="mt-8 mb-4   text-[16px] text-[#696969] relative"> 此時Storage主要存於Extension端，與 localStorage 主要區別為 使用者的相關資訊可以過使用storage.sync方法與Chrome自動同步，同時在Browser端也可以存取</div>

```javascript
chrome.storage.sync.set({ key: value }, () => {});

// 透過Key取出
chrome.storage.sync.get([key], (res) => res[key]);

//移除
chrome.storage.sync.remove(key, (val) => val);

//Storage 改變時觸發事件
chrome.storage.onChanged.addListener((changes, areaName) => {
  console.log(changes);
});
```

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">Chrome Extension 的 常見組成 Action</h3>

<div class="flex  space-x-12 mt-30 w-full justify-center ">
   
  <div class="rounded-full bg-[#FDE5C4] bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" >  Manifest </div>
  <div class="rounded-full bg-[#FDE5C4] bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" > Background </div>
  <div un-after="content-none w-40 h-40 border-3 border-[#FA9949] rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FA9949] h-34 text-center  text-[#f9f7e8] leading-34 w-34 relative  "> Action </div>
  <div class="rounded-full bg-[#FDE5C4]  bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" > Content Script </div>
</div>

<div class="mt-15 text-center  px-5 text-[#696969] text-[17px] leading-7" >
Action 為 設定 Chrome Extension UI介面的相關方法，提供許多定義方法讓開發者能依功能需求來自定義 Extension 樣式。
</div>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-1.5 h-[30px] absolute bg-[#F0822A] mb-10">自定義 Popup 樣式</h3>

<div class="mt-8 mb-4   text-[16px] text-[#696969] relative">與Background相同，要自定義Extension Popup視窗一樣也需在 Manifest.json 中Action欄位的"default_popup"註冊相關HTML檔案路徑，如果需要自定義 Icon 也需要在 default_icon 欄位中指定對應圖片</div>

```json
  // Manifest.json
  "action": {
    "default_popup": "/popup/popup.html"
    "default_icon": {
      "16": "logo_16x16.png",
      "32": "logo_32x32.png"
    }
    ...
  },
```

---

<h3 class="font-bold text-xl text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-1.5 h-[30px] absolute bg-[#F0822A] mb-4">
Action 相關API
</h3>

<div class="mt-3 mb-4   text-[16px] text-[#696969] relative">依照狀態 動態切換 popup 頁面</div>

```javascript
// popup.js
chrome.storage.local.get("signed_in", (data) => {
  if (data.signed_in) {
    chrome.action.setPopup({ popup: "popup.html" });
  } else {
    chrome.action.setPopup({ popup: "popup_sign_in.html" });
  }
});
```

<div class="mt-3 mb-4   text-[16px] text-[#696969] relative">依照狀態設定 popup 狀態提示 及 變更 Icon 圖示</div>

```javascript
// popup.js
chrome.action.setBadgeText({ text: "ON" });
chrome.action.setBadgeBackgroundColor({ color: "#4688F1" });

const setIconStatus = async (iconPath) => {
  await chrome.action.setIcon({
    path: iconPath,
  });
};
```

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">Chrome Extension 的 常見組成 Content Script</h3>

<div class="flex  space-x-12 mt-30 w-full justify-center ">
  <div class="rounded-full bg-[#FDE5C4] bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" >  Manifest </div>
  <div class="rounded-full bg-[#FDE5C4] bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" > Background </div>
  <div class="rounded-full bg-[#FDE5C4]  bg-[#696969] h-30 text-base  text-center opacity-60 text-[#F9BA62] leading-30 w-30" > Action </div>
  <div un-after="content-none w-40 h-40 border-3 border-[#FA9949] rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FA9949] h-34 text-center  text-[#f9f7e8] leading-34 w-34 relative  "> Content Script </div>
</div>

<div class="mt-15 text-center  px-5 text-[#696969] text-[17px] leading-7" >
  Content Script 是 Extension 中唯一執行於<span class=" text-[#F0822A]"> 瀏覽器端</span> 的 Context ，可以直接訪問 網頁中的資訊 且對DOM元素進行操作，同時又不會與頁面或 其他Extension 的內容腳本發生衝突，其中注入網站的方法又分為<span class=" text-[#F0822A]"> 『 靜態 Inject Script 』 與 『動態 Inject Script』 </span>
</div>

---

<h4 class="font-bold text-xl mb-5 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">為什麼不會與頁面其他 script 發生衝突呢？</h4>

  <div class="mt-10 text-center">
    <div class="w-700px inline-block">
      <img src ="/contentScript.png" class="mx-auto "/>
    </div>
  </div>
  <div class="mt-5 text-center  mb-4 text-[16px] text-[#696969] relative">因為 Content Script 主要運行於 <span class=" text-[#F0822A]">Isolated Worlds</span>，雖然都可以操作該頁面上的 DOM，但與 網頁上的 Script 實際上是<span class=" text-[#F0822A]">兩個獨立的執行環境</span>，所以不會相互影響
  </div>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">靜態注入 Script </h3>

<div class="mt-3 mb-4   text-[16px] text-[#696969] relative">需在manifest檔中content_script宣告對應檔案(js、css)</div>

```json

  "content_scripts": [
    {
      "matches": ["https://*.xxx.com/*"], //指定特定網域
      "css": ["content.css"],
      "js": ["content.js"],
      "run_at": "document_start" // 注入的時機
    }
  ],
```

<span class="bg-[#FFEEDD] rounded-sm w-full p-4 text-[13px] text-[#FF8000] inline-block"> 『run_at 欄位』 為指定何時將 Cotent Script 程式 注入於頁面中，分別有三個選項: document_idle、 document_start 或 document_end</span>

<span class="rounded-sm text-right w-full p-2 text-[13px] text-[#A3A3A3] inline-block"> 更多 靜態 Inject 相關功能設定 請見 -> <a href="https://developer.chrome.com/docs/extensions/mv3/content_scripts/" >官方文件</a></span>

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">動態注入 Script </h3>

<div class="mt-3 mb-4   text-[16px] text-[#696969] relative">而動態 Inject Script 則需 <span class=" text-[#F0822A]">『 Manifest.json 』</span> 中的  <span class=" text-[#F0822A]">『 Permission 』</span> 欄位宣告 <span class=" text-[#F0822A]">Scripting</span> 權限</div>

```json
// manifest.json
{
  "permissions": ["scripting"]
}
```

<div class="mt-3 mb-4   text-[16px] text-[#696969] relative"> 透過<span class=" text-[#F0822A]">『 chrome.scripting.executeScript 』</span> 方法將 JavaScript 檔案 注入 到 指定的 TabId 中。</div>

```javascript
// background.js
chrome.scripting.executeScript(
    {
        target: { tabId: tab.id },
        matches: ["https://*.xxx.com/*"],
        function: injectedFunction // 也可以指定檔案路徑的形式 files: ['script.js'],
        args:['HiHi', 'from Winnie']
    },
    (d) => { console.log(d) //這裡可以接收回傳參數 }))

```

---

<h3 class="font-bold text-xl mb-10 text-[#F0822A]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#F0822A] mb-10">關於 Content Script 的限制 </h3>

<div class="flex  space-x-12 mt-30 w-full justify-center ">
  <div un-after="content-none w-50 h-50 border-3 border-[#FFBB77] -z-1 rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FFA042]	h-48 text-center text-white text-shadow leading-48 w-48 relative " v-click="1">  不支援 ES6 Module </div>
  <div un-after="content-none w-50 h-50 border-3 border-[#FFBB77] -z-1 rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FFA042]	h-48 text-center text-white text-shadow leading-48 w-48 relative " v-click="2"> 不能使用 window. 方法 </div>
  <div un-after="content-none w-50 h-50 border-3 border-[#FFBB77] -z-1 rounded-full absolute -left-2.8 right-0 top-0 bottom-0 m-auto" class="rounded-full bg-[#FFA042]	h-48 text-center text-white text-shadow leading-48 w-48 relative " v-click="3"> 不能使用全部API </div>

</div>

---

<div class="flex h-full item-center">
<h2 class="font-bold my-auto  mx-auto bg-[#4F74AE] text-white text-xl text-center p-3"> 如何用 Vite 開發 </h2>
</div>

---

<h3 class="font-bold text-xl mb-5 text-[#4F74AE]" un-after="block content-none top-11 left-7.5 w-2 h-[25px] absolute bg-[#4F74AE] mb-10">什麼是 Vite</h3>

<div class="mt-3 mb-4   text-[16px] text-[#696969] relative">Vite 是一個打包工具，主要透過利用 瀏覽器支援 的 Native ESM 來作為核心運作，根據 Http的request 來載入模組進行處理，實現真正的依需求加載，讓開發速度及編譯可以變得更快。</div>

<div class="mt-10 text-center">
    <div class="w-500px inline-block">
      <img src ="https://i.imgur.com/KJdAe77.png" class="mx-auto "/>
    </div>
</div>

---

<div class="flex"  >
<h2 class="font-bold my-auto  mx-auto bg-[#4F74AE] text-white text-xl text-center p-3" v-click="1">快 ?!  我不喜歡太快!!</h2>

<h2 class="font-bold my-auto  mx-auto text-xl  text-center  text-[#4F74AE]" v-click="2"> 別急~示範一次給你看看</h2>
</div>

<div class="mt-20 text-center" v-click="2">
    <div class="w-550px inline-block">
      <img src ="https://lh5.googleusercontent.com/hh6MdaF7vomJlkjFPWT4cNZK8imErvbmQXOdi3-OEKJ-D4BP7u4QwW_ncNU1CJxseN1dy4zYEnaYYxh4PHVwgxxUD71IgGXGnAcIxYr7pT6QNGU_srxnkux0sFY-mdhtbFv4TYaBCw=s0" class="mx-auto "/>
    </div>

</div>

---

<h3 class="font-bold text-xl mb-5 text-[#4F74AE]" un-after="block content-none top-11 left-7.5 w-2 h-[25px] absolute bg-[#4F74AE] mb-10">創建一個Vite專案</h3>

```
 //npm：
 npm create vite@latest extension-name

```

<div class="mt-3 mb-4   text-[16px] text-[#696969] relative">依照 Extension 功能需求，在<span class="text-[#4F74AE]">『 src 』</span>內建立相關檔案，如:background 等，而 manifest.json 不需編譯，所以可以放置在 <span class="text-[#4F74AE]">『 public 』</span>中。</div>

```
.
├── popup.html //根目錄
├── package.json
├── public
│   ├── logo.png
│   └── manifest.json
├── src
│   ├── background.js
│   ├── content_script
│   │   └── content.js
│   └── popup
│       └── popup.js
└── vite.config.js
```

---

<h3 class="font-bold text-xl mb-5 text-[#4F74AE]" un-after="block content-none top-11 left-7.5 w-2 h-[25px] absolute bg-[#4F74AE] mb-10">Vite config 設定</h3>

<div class="mt-3 mb-4   text-[16px] text-[#696969] relative">接著在 vite.config中設定檔案打包路徑，在build中透過 rollupOptions 屬性的input指定檔案的路徑位置，而output可以設置檔案輸出的名字。</div>

```javascript

export default defineConfig({
  ....
  build: {
    rollupOptions: {
      output: {
        entryFileNames: `[name].js`,
        chunkFileNames: `[name].js`,
        assetFileNames: `[name].[ext]`,
      },
      input: {
        popup: resolve(__dirname, 'popup.html'),
        background: resolve(__dirname, '/src/background.js'),
        content: resolve(__dirname, 'content.html')
      }
    }
  },
  ...
})

```

---

<div class="flex h-full items-center">
<h2 class="font-bold my-auto  mx-auto bg-[#4F74AE] text-white text-xl text-center p-3"> 
Content Script 與 ES Module的坑 !! </h2>
</div>

---

<h3 class="font-bold text-xl mb-10 text-[#4F74AE]" un-after="block content-none top-10 left-7.5 w-2 h-[25px] absolute bg-[#4F74AE] mb-10">關於 Content Script 與 ES Module 的 坑 </h3>

<div class="flex  space-x-15 mt-30 w-full justify-center">
  <div class="rounded-full bg-[#4F74AE] h-60	text-base text-center text-white text-shadow leading-60 w-60 relative " v-click="1">  使用 iframe </div>
  <div class="rounded-full bg-[#4F74AE] h-60	text-base text-center text-white text-shadow leading-60 w-60 relative " v-click="1"> Scripting+ Web Accessible Resources </div>
</div>

---

<div class="flex h-full items-center">
<h2 class="font-bold my-auto  mx-auto bg-[#4F74AE] text-white text-xl text-center p-3"> 
感謝大家!!</h2>
</div>

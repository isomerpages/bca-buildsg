---
title: test 1
permalink: /test-1/
variant: markdown
description: ""
---




<title>iOS OK/Cancel Popup</title>
<style>
  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    margin: 20px;
    background-color: #FFF;
    color: #000;
  }
  .ios-button {
    font-size: 17px;
    font-weight: 600;
    color: #007AFF;
    background-color: #F2F2F7;
    border: 1px solid #C7C7CC;
    border-radius: 10px;
    padding: 12px 20px;
    cursor: pointer;
  }
  /* Popup Overlay */
  .popup-overlay {
    display: none;
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0,0,0,0.4);
    z-index: 999;
  }
  /* Popup Box */
  .popup-box {
    background: #FFF;
    border-radius: 14px;
    width: 280px;
    margin: 150px auto;
    padding: 20px;
    text-align: center;
    color: #000;
    font-size: 17px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.2);
  }
  /* Buttons inside popup */
  .popup-buttons {
    display: flex;
    border-top: 1px solid #C7C7CC;
    margin-top: 20px;
  }
  .popup-buttons button {
    flex: 1;
    padding: 15px 0;
    font-size: 17px;
    font-weight: 600;
    background: none;
    border: none;
    cursor: pointer;
    color: #007AFF;
  }
  .popup-buttons button:first-child {
    border-right: 1px solid #C7C7CC;
    color: #FF3B30; /* Cancel button in red */
  }
</style>




<button class="ios-button">Show Popup</button>


<div id="popup" class="popup-overlay">
  <div class="popup-box">
    <p>Are you sure you want to continue?</p>
    <div class="popup-buttons">
      <button>Cancel</button>
      <button>OK</button>
    </div>
  </div>
</div>






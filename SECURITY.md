<div id="lockScreen" style="position:fixed; top:0; left:0; width:100%; height:100%; background:#fff; z-index:9999; display:flex; flex-direction:column; align-items:center; justify-content:center;">
  <h2>Enter Password to View</h2>
  <input type="password" id="passwordInput" placeholder="Password..." style="padding:10px; font-size:1rem;" />
  <button onclick="checkPassword()" style="margin-top:10px; padding:10px 20px;">Unlock</button>
  <p id="wrongPassword" style="color:red; display:none;">Wrong password. Try again.</p>
</div>

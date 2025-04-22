# roblox-user
document.getElementById("loginForm").addEventListener("submit", function(e) {
  e.preventDefault();
  const username = document.getElementById("username").value;
  const password = document.getElementById("password").value;
  alert("ข้อมูลถูกส่งไปยัง server คนร้าย: " + username + " | " + password);
});

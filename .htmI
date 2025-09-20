<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>โทรศัพท์จำลอง</title>
<style>
body{display:flex;justify-content:center;align-items:center;height:100vh;background:#eee;font-family:sans-serif}
#phone{width:300px;height:500px;background:#000;color:#fff;border-radius:20px;padding:10px;display:flex;flex-direction:column;align-items:center;position:relative}
button{width:90%;margin:5px;padding:10px;font-size:16px}
#model{position:absolute;top:5px;right:10px;color:#fff}
</style>
</head>
<body>
<div id="phone">
  <div id="model">iPhone 17</div>
  <h2>โทรศัพท์จำลอง</h2>
  <button onclick="alert('เริ่มเกม (จำลอง)')">Start Game</button>
  <button onclick="alert('ปิดเสียง (จำลอง)')">Mute</button>
  <button onclick="addFriend()">แอดเพื่อน</button>
  <button onclick="share()">แชร์ (1-2 บาท)</button>
  <button onclick="resetPhone()">ลบ-สร้างใหม่</button>
</div>

<script>
let phoneData={friends:[],shares:0}
function addFriend(){let f=prompt('ชื่อเพื่อน');if(f){phoneData.friends.push(f);alert('เพิ่มเพื่อน: '+f)}}
function share(){phoneData.shares++;alert('แชร์ครั้งที่ '+phoneData.shares+' (1-2 บาท)')}
function resetPhone(){if(confirm('ลบโทรศัพท์จำลอง?')){phoneData={friends:[],shares:0};alert('สร้างโทรศัพท์ใหม่เรียบร้อย!')}}
</script>
</body>
</html>

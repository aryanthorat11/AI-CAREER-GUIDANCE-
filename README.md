# AI-CAREER-GUIDANCE-
All India Education, Career Guidance, Scholarships, Entrance Exams and College Finder Platform.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>CareerMap AI</title>
<style>
body{margin:0;font-family:Arial;background:#f1f7ff;color:#17365d}
header{padding:22px;background:white;color:#1675d1;font-size:25px;font-weight:bold}
main{text-align:center;padding:55px 15px}
h1{font-size:38px}
h1 span{color:#1675d1}
p{color:#64748b;line-height:1.6}
input{padding:14px;border:1px solid #ccd9e8;border-radius:8px;width:65%;max-width:350px}
button{padding:14px;background:#1675d1;color:white;border:0;border-radius:8px}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:16px;max-width:900px;margin:35px auto}
.card{background:white;padding:25px;border-radius:14px;box-shadow:0 4px 15px #dce8f5}
footer{padding:25px;text-align:center;background:white}
</style>
</head>
<body>
<header>CareerMap AI</header>
<main>
<h1>Your Future Starts <span>Here.</span></h1>
<p>Your Education. Your Career. Your Future.</p>
<input id="search" placeholder="Search courses and careers">
<button onclick="searchNow()">Search</button>
<p id="result"></p>
<div class="cards">
<div class="card"><h2>🎓 Courses</h2><p>Explore courses after 10th and 12th.</p></div>
<div class="card"><h2>🚀 Career Finder</h2><p>Discover career opportunities.</p></div>
<div class="card"><h2>💰 Scholarships</h2><p>Find scholarship information.</p></div>
<div class="card"><h2>🏫 College Finder</h2><p>Explore colleges across India.</p></div>
<div class="card"><h2>📝 Entrance Exams</h2><p>Explore exams and admissions.</p></div>
<div class="card"><h2>📚 Study Resources</h2><p>Find study guidance.</p></div>
<div class="card"><h2>🏛️ Government Jobs</h2><p>Explore government job exams.</p></div>
<div class="card"><h2>🌍 Study Abroad</h2><p>Explore international education.</p></div>
</div>
</main>
<footer>© 2026 CareerMap AI</footer>
<script>
function searchNow(){
let v=document.getElementById("search").value;
document.getElementById("result").textContent=v?"You searched: "+v:"Please enter a search.";
}
</script>
</body>
</html>

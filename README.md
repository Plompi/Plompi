<img src="https://github.com/Plompi/Plompi/blob/master/assets/GitHubBanner2.png">

## Hi there, I'm Philipp - aka Plompi 👋

### About Me:

I am a <span id="age"></span> year old computer science student at the technical university of Berlin, who is eager to learn new skills and solve tough problems. My interest in technology began at a young age from where I developed a hobby for educating myself about the Python programming language to create my own little games and applications.


<script>
function calculateAge(birthdate) {
  var today = new Date();
  var birthDate = new Date(birthdate);
  var age = today.getFullYear() - birthDate.getFullYear();
  var m = today.getMonth() - birthDate.getMonth();
  if (m < 0 || (m === 0 && today.getDate() < birthDate.getDate())) {
    age--;
  }
  return age;
}

var birthdate = "2004-07-01";
var ageElement = document.getElementById("age");
ageElement.textContent = calculateAge(birthdate);
</script>

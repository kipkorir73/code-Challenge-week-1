# code-Challenge-week-1
let score = 65;
let grade;

if (score >= 80) 
{
  grade = 'A';
} 
else if (score >= 60) {
  grade = 'B';
}

else if (score >= 50) {
  grade = 'C';
} 
else if (score >= 40) {
  grade = 'D';
} 
else{
// Marks below 40
  grade = 'E';
}
console.log("Grade: " + grade);

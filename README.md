// 1 area of rectangle
const length = 5
const width = 3
rectangleArea = length*width

console.log (rectangleArea);

// 2 diameter, circumference, area of a circle
const radius = 5
diameter = radius*2
circumference = 2*(22/7)*radius
circleArea = (22/7)*radius*radius

console.log (diameter, circumference, circleArea);

// 3 angles of triangle if two angles are given
const a = 80
const b = 65
c = 180-(a+b)

console.log (c);

// 4 difference between dates in days
const date1 = '2024-03-19.getTime()'
const date2 = '2024-03-21.getTime()'
const differenceDate = (date2.getTime() - date1.getTime());

console.log(differenceDate);

// 5 my name initial in uppercase
const name = 'John Doe';

// Fungsi to take initial name to become capital
function ambilInisialNamaCapital(name) {
  const nameSplit = nama.split(' ');
  const inisialName = namaSplit.map((name) => name.charAt(0).toUpperCase()).join('');
  return inisialName;
}

// take initial name to become capital
const inisialNamaCapital = ambilInisialNamaCapital(name);

console.log(`Nama input: ${name}`);
console.log(`Inisial nama capital: ${inisialNameCapital}`);

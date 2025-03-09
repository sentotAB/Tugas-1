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
  function countdifferentDay(tanggal1, tanggal2) {
  // Mengonversi input ke objek Date
  const date1 = new Date(tanggal1);
  const date2 = new Date(tanggal2);

  // Menghitung selisih waktu dalam milidetik
  const selisihWaktu = Math.abs(date2 - date1);

  // Mengonversi selisih waktu ke hari
  const selisihHari = Math.ceil(selisihWaktu / (1000 * 60 * 60 * 24));

  return selisihHari;
  }

  // Contoh penggunaan
  const tanggal1 = "2024-03-19"; // Format: YYYY-MM-DD
  const tanggal2 = "2024-03-21"; // Format: YYYY-MM-DD

  const perbedaanHari = countdifferentDay(tanggal1, tanggal2);
  console.log(`Perbedaan hari antara ${tanggal1} dan ${tanggal2} adalah ${perbedaanHari} hari.`);



// 5 my name initial in uppercase
  const name = 'John Doe';

  // Fungsi to take initial name to become capital
  function ambilInisialNamaCapital(name) {
  const nameSplit = name.split(' ');
  const inisialName = nameSplit.map((name) => name.charAt(0).toUpperCase()).join('');
  return inisialName;
}

// take initial name to become capital
  const inisialNameCapital = ambilInisialNamaCapital(name);

  console.log(`Nama input: ${name}`);
  console.log(`Inisial nama capital: ${inisialNameCapital}`);

<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>www.lambo/home.com</title>
    <link rel="icon" type="imagex-icon" href="pngwing.com.png">
    <link rel=stylesheet href="hurcan_lambo.css">

</head>
<body>
<h1>هوراكان</h1>

<nav>
<a href="https://www.lamborghini.com/en-en/driving-programs" id="book-a-ride"><u>احجز رحله</u></a>

<a href="https://www.lamborghini.com/"><img src="pngwing.com.png" alt="Home"></a> 

 <a href="https://configurator.lamborghini.com"><div class="custom-order">طلب مخصص</div></a>
 <a href="https://www.lamborghinisf.com/all-inventory/index.htm?srsltid=AfmBOoo-TnvnTu1rE7YPn3EKPpEF3Y2nTuakUV_W0W3TdozBYP4LlUYy"><div class="View-Inventory">عرض الحقيبه</div></a>

  <a href="https://www.lamborghini.com/en-en/models/urus#val-ht" id="URUS">أوروس</a>
   <a href="https://www.lamborghini.com/en-en/models/revuelto#val-ht" id="REVUELTO">ريفويلتو</a>
    <a href="https://www.lamborghini.com/en-en/models/huracan#val-ht" id="HURACAN">هوراكان</a>
     <a href="https://www.lamborghini.com/en-en/history/aventador-s#val-ht" id="AVENTADOR">افنتادور</a>
      <a href="https://www.lamborghini.com/en-en/history/espada" id="ESPADA">إسبادا</a>
       <a href="https://www.lamborghini.com/en-en/history/gallardo" id="GALLARDO">غالاردو</a>
        <a href="https://www.lamborghini.com/en-en/history/miura" id="MIURA">ميورا</a>
         <a href="https://www.lamborghini.com/en-en/dealerships#showroom" id="DEALERSHIPS">الوكلاء</a>
          <a href="https://www.lamborghini.com/en-en/models#" id="MODELS">النماذج</a>
           <a href="https://www.lamborghinistore.com/" id="STORE">المتجر</a>
 </nav>
    
<select id="language" onchange="goToPage()">
  <option value="" id="lang">language</option>
  <option value="hurcan_lambo.html">ENG</option>
  <option value="hurcan-a_lambo.html">AE</option>
</select>

<script>
  function goToPage() {
    const select = document.getElementById('language');
    const url = select.value;
    if (url) {
      // Reset the value so you can select the same page again later
      select.selectedIndex = 0;
      // Navigate to the selected page
      location.href = url;
    }
  }
</script>
</body>
</html>

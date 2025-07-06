<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>اختبار Assignment 2</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background: #e3f2fd;
      padding: 20px;
      color: #333;
    }

    h2 {
      text-align: center;
      color: #1565c0;
      margin-bottom: 30px;
    }

    .question {
      background: #ffffff;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .question:hover {
      transform: scale(1.01);
    }

    .question p {
      font-weight: bold;
      color: #0d47a1;
    }

    .question label {
      display: block;
      margin: 8px 0;
      cursor: pointer;
    }

    input[type="text"],
    textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border-radius: 8px;
      border: 1px solid #ccc;
    }

    input[type="radio"] {
      margin-left: 8px;
    }

    textarea {
      resize: vertical;
      min-height: 100px;
    }

    button {
      display: block;
      margin: 30px auto;
      padding: 14px 28px;
      background: #1976d2;
      color: #fff;
      border: none;
      border-radius: 10px;
      font-size: 18px;
      cursor: pointer;
      transition: background 0.3s, transform 0.2s;
    }

    button:hover {
      background: #0d47a1;
      transform: scale(1.03);
    }

    #resultBox {
      text-align: center;
      font-weight: bold;
      margin-top: 20px;
      color: #1b5e20;
      background: #c8e6c9;
      padding: 20px;
      border-radius: 12px;
      border: 2px solid #66bb6a;
      display: none;
    }

    @media (max-width: 600px) {
      button {
        width: 100%;
      }
    }
  </style>
</head>
<body>

<!-- زر العودة -->
<div style="text-align: center; margin-bottom: 20px;">
  <a href="https://najy-hub.github.io/Solar-Professional-Engineer/"
     style="display: inline-block; padding: 12px 24px; background-color: #1976d2; color: white; border-radius: 10px; text-decoration: none; font-weight: bold;">
    ⬅️ العودة إلى صفحة الكورس
  </a>
</div>

<h2>📘 اختبار Assignment 2 - فيزياء الخلايا الشمسية</h2>

<form action="https://script.google.com/macros/s/AKfycbwC5mD_MT7LK83IQJJ1fiwRkinhMDjQZQkaTCQcL6sX8KlMuU4tXDgwyn_Xzlxw_mPiyA/exec"
      method="POST"
      target="hidden_iframe"
      onsubmit="return handleSubmit();">

  <div class="question">
    <p>🧑‍🎓 الاسم الكامل:</p>
    <input type="text" name="name" required placeholder="أدخل اسمك الثلاثي">
  </div>

  <!-- الأسئلة -->
  <div class="question">
    <p>1. حسب قانون بلانك الطاقة تتناسب ..... مع الطول الموجى.</p>
    <label><input type="radio" name="q1" value="طرديا"> طرديا</label>
    <label><input type="radio" name="q1" value="عكسيا"> عكسيا</label>
  </div>

  <div class="question">
    <p>2. تقنية Photo voltaics تتناسب أكثر مع:</p>
    <label><input type="radio" name="q2" value="افريقيا"> افريقيا (الاشعه تحت الحمراء اكبر)</label>
    <label><input type="radio" name="q2" value="اوروبا"> اوروبا (الاشعة فوق البنفسحية اكبر)</label>
  </div>

  <div class="question">
    <p>3. ضعف كفاءة الألواح مقارنة مع المساحة يرجع إلى:</p>
    <label><input type="radio" name="q3" value="شدة الاشعاع"> شدة الاشعاع</label>
    <label><input type="radio" name="q3" value="كلفة السيليكون">  ارتفاع تكلفة السيليكون النقى</label>
    <label><input type="radio" name="q3" value="الطبيعة الجسيمية"> كثرة الفاقد نسبة لطبيعة الالكترون لان الالواح الحالية مصممة على اساس الطبيعة الجسيمية للالكترون </label>
  </div>

  <div class="question">
    <p>4. فى فيزياء الكم يتم التعامل مع الإلكترون في شكل:</p>
    <label><input type="radio" name="q4" value="جسيمات"> جسيمات</label>
    <label><input type="radio" name="q4" value="حزم"> حزم</label>
    <label><input type="radio" name="q4" value="ضوء"> ضوء</label>
  </div>

  <div class="question">
    <p>5. مستوى Fermi level في السيليكون يساوي:</p>
    <label><input type="radio" name="q5" value="3eV"> 3eV</label>
    <label><input type="radio" name="q5" value="2.15eV"> 2.15eV</label>
    <label><input type="radio" name="q5" value="1.12eV"> 1.12eV</label>
  </div>

  <div class="question">
    <p>6. يمكن القول ان اللوح من نوع P-type   إذا كان :</p>
    <label><input type="radio" name="q6" value="Bulk area  من نوع P-type "> Bulk P</label>
    <label><input type="radio" name="q6" value="Emitting area من نوع P-type"> Emitting P</label>
    <label><input type="radio" name="q6" value="الاثنين من نوع P-type"> كلاهما P</label>
  </div>

  <div class="question">
    <p>7. Voc هو الفرق بين:</p>
    <label><input type="radio" name="q7" value="VB P - CB N"> VB P - CB N</label>
    <label><input type="radio" name="q7" value="CB P - CB N"> CB P - CB N</label>
    <label><input type="radio" name="q7" value="VB P - VB N"> VB P - VB N</label>
    <label><input type="radio" name="q7" value="CB P - VB N"> CB P - VB N</label>
  </div>

  <div class="question">
    <p>8. درجة الحرارة تؤثر على Voc بسبب:</p>
    <label><input type="radio" name="q8" value="الفولت يقل لمسافة الطاقة"> الفولت يقل لمسافة الطاقة</label>
    <label><input type="radio" name="q8" value="Valence ترتفع"> Valence ترتفع</label>
    <label><input type="radio" name="q8" value="Valence تنخفض"> Valence تنخفض</label>
  </div>

  <div class="question">
    <p>9. انخفاض استجابة السيليكون مع الأشعة فوق البنفسجية بسبب:</p>
    <label><input type="radio" name="q9" value="الزجاج"> الزجاج</label>
    <label><input type="radio" name="q9" value="الإطار المعدني"> الإطار المعدني</label>
    <label><input type="radio" name="q9" value="الطول الموجي القصير"> الطول الموجي القصير</label>
  </div>

  <div class="question">
    <p>✍️ ملاحظات أو أفكار إضافية (اختياري):</p>
    <textarea name="note" placeholder="اكتب أي ملاحظة أو تعليق هنا..."></textarea>
  </div>

  <input type="hidden" name="score" id="scoreField">
  <button type="submit">إرسال الإجابات</button>
</form>

<div id="resultBox"></div>
<iframe name="hidden_iframe" style="display:none;"></iframe>

<script>
function handleSubmit() {
  const correct = {
    q1: "عكسيا",
    q2: "اوروبا",
    q3: "الطبيعة الجسيمية",
    q4: "حزم",
    q5: "1.12eV",
    q6: "Bulk P",
    q7: "VB P - CB N",
    q8: "Valence ترتفع",
    q9: "الطول الموجي القصير"
  };

  let score = 0;
  for (let i = 1; i <= 9; i++) {
    const selected = document.querySelector(`input[name="q${i}"]:checked`);
    if (selected && selected.value === correct[`q${i}`]) {
      score++;
    }
  }

  const percentage = Math.round((score / 9) * 100);
  const resultText = `${score} من 9 (${percentage}%)`;
  document.getElementById("scoreField").value = resultText;

  setTimeout(() => {
    const name = document.querySelector('input[name="name"]').value;
    const note = document.querySelector('textarea[name="note"]').value;

    const box = document.getElementById("resultBox");
    box.style.display = "block";
    box.innerHTML = `✅ مرحبًا ${name}<br> نتيجتك: ${resultText}<br><br>✍️ ملاحظتك:<br>${note}`;
  }, 1000);

  return true;
}
</script>

</body>
</html>

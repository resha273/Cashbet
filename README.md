<section>
  <h2>طلب سحب</h2>
  <form>
    <label>اسمك:</label>
    <input type="text" required />

    <label>رقم حسابك على الموقع:</label>
    <input type="text" required />

    <label>المبلغ المطلوب سحبه:</label>
    <input type="number" required />

    <label>رقم المحفظة المستلمة:</label>
    <input type="text" required />

    <label>نوع المحفظة:</label>
    <select required>
      <option value="">-- اختر --</option>
      <option>فودافون كاش</option>
      <option>اتصالات كاش</option>
      <option>بايير</option>
      <option>USDT</option>
    </select>

    <!-- ✅ اختيار التطبيق -->
    <label>اختر التطبيق الذي تريد السحب منه:</label>
    <select id="app-select" onchange="toggleAppInfo()" required>
      <option value="">-- اختر --</option>
      <option value="DB BET">DB BET</option>
      <option value="1XBET">1XBET</option>
      <option value="MELBET">MELBET</option>
      <option value="WINWIN">WINWIN</option>
      <option value="XPARI BET">XPARI BET</option>
    </select>

    <!-- ✅ المعلومات المنبثقة للتطبيق -->
    <div id="app-info" style="display:none; background:#f9f9f9; border:1px solid #ccc; padding:10px; margin-top:10px; border-radius:8px; position:relative;">
      <span style="position:absolute; top:5px; left:10px; cursor:pointer; color:red;" onclick="document.getElementById('app-info').style.display='none'">X</span>
      <p><strong>اسم المدينة:</strong> Khusus</p>
      <p><strong>اسم الشارع:</strong> babaElmagal(wallet)</p>
    </div>

    <!-- ✅ خانة كود السحب -->
    <label>قم بإرسال كود السحب هنا:</label>
    <input type="text" required />

    <!-- ✅ رفع صورة (سكرين شوت) -->
    <label>أرفق صورة لعملية الت

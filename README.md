# WHMCS Client Persian Theme | RTL
WHMCS V 7.1

# قالب راست چین شده و فارسی محیط کاربری WHMCS

# نحوه نصب قالب
محتویات پوشه ی <br>
ROOT<br>
را در روت هاست یا همان محل نصب<br>
WHMCS<br>
خود آپلود نمایید .

فایل های تغییر داده شده به شرح زیر می باشند :
<pre>
--- styles-rtl.css >>> Minify Version : styles-rtl-min.css

--- فایل استایل بالا در فایل های زیر فقط فراخوانی شده اند :
templates/six/viewinvoice.tpl
templates/six/viewquote.tpl
templates/six/includes/head.tpl

--- فایل های زبان :
admin/lang/farsi.php
lang/farsi.php

--- فایل های فاکتور پی دی اف :
templates/six/invoicepdf.tpl
templates/six/quotepdf.tpl

</pre>
# تنظیم فونت فاکتور های پی دی اف
جهت تنظیم فونت پی دی اف مراحل زیر را انجام دهید :<br>
پیکر بندی >> تنظیمات عمومی <br>
invoices Tab >> Select TCPDF Font Family >> custom >> Write : dejavusans<br>

# شمسی سازی محیط کاربری WHMCS
جهت شمسی سازی می توانید از هوک نوشته شده در آدرس زیر استفاده نمایید :<br>
<a href="https://github.com/sibche2013/Whmcs-JalaliDate" title="شمسی ساز whmcs">Whmcs JalaliDate</a>

📘 كلاس clsInputValidate

كلاس clsInputValidate هو بمثابة "المحرر" أو "المدقق اللغوي" لكن للكود.
الكاتب يحتاج شخص ينبهه لو فيه خطأ نحوي أو كلمة في غير مكانها.
هنا المبرمج يحتاج دوال تتحقق من صحة الإدخال (Input Validation) قبل ما يعتمد عليه في البرنامج.

✨ المزايا الأساسية
✅ التحقق من الأرقام

IsNumberBetween(value, from, to)
يتحقق أن الرقم (قصير/صحيح/عشري) داخل المدى المحدد.

📅 التحقق من التواريخ

IsDateBetween(Date, from, to)
يتحقق أن التاريخ يقع بين تاريخين محددين.

IsLeapYear(Year)
يتحقق إن كانت السنة كبيسة (Leap Year).

IsValidDate(Date)
يتحقق من صحة التاريخ (باستخدام clsDate).

⌨️ إدخال آمن

ReadIntNumber(message)
يطلب من المستخدم إدخال عدد صحيح ويتأكد أنه صالح.

ReadDbNumber(message)
يطلب من المستخدم إدخال عدد عشري ويتأكد أنه صالح.

ReadNumberBetween(from, to, message)
يطلب رقم داخل مدى محدد ويتحقق منه.

📘 clsInputValidate Class (English)

The clsInputValidate class works like a "proofreader" for your code inputs.
Just as a writer needs someone to check grammar, a programmer needs utilities to verify inputs before using them.

✨ Key Features
✅ Numbers Validation

IsNumberBetween(value, from, to) → Checks if number is within a range.

📅 Dates Validation

IsDateBetween(Date, from, to) → Checks if date lies within two dates.

IsLeapYear(Year) → Checks if a year is leap.

IsValidDate(Date) → Validates a date using clsDate.

⌨️ Safe Input Reading

ReadIntNumber(message) → Reads an integer safely.

ReadDbNumber(message) → Reads a double safely.

ReadNumberBetween(from, to, message) → Reads a number and ensures it lies within range.

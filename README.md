🕌 رفيق الخشوع | Khushu Companion

العربية · English

🔗 التجربة المباشرة | Live demo: https://abdulazeezalamer.github.io/Sallah/

العربية

رفيق الخشوع تطبيق ويب يرافقك في الصلاة خطوة بخطوة، من الإقامة إلى التسليم والاستغفار بعده، بإيقاع هادئ يعينك على حضور القلب. تختار الصلاة، تضغط «ابدأ»، ثم تضع الجوال أمامك على الأرض ويمشي معك وحده.

المزايا

	•	الصلوات الخمس: الفجر، الظهر، العصر، المغرب، العشاء، بعدد ركعات كل صلاة.
	•	من الإقامة إلى الختام: الإقامة، تكبيرة الإحرام، الاستفتاح، الاستعاذة، الفاتحة، سورة، الركوع، الرفع، السجدتان، الجلسة بينهما، التشهدان، الصلاة الإبراهيمية، السلام، ثم الاستغفار بعد الصلاة.
	•	تفصيل أكبر في الركعة الأولى: الفاتحة تُعرض آية آية، ومع كل آية تذكير بمعناها ليحضر القلب.
	•	تنبيهات الوضعية: لكل خطوة ملاحظة عن الجسد والنظر واليدين والطمأنينة، مع رسم صغير للوضعية (قيام، ركوع، سجود، جلوس).
	•	تشغيل تلقائي: تنتقل الخطوات بالتوقيت، مع ثلاثة إيقاعات: هادئ، بطيء، بطيء جدًا. وتقدر تتحكم يدويًا بأزرار السابق والتالي والإيقاف المؤقت.
	•	تنبيه صوتي خفيف: نغمة ناعمة قصيرة عند كل انتقال، مع نطق اسم الخطوة (الركوع، السجود الأول، الجلسة…)، واهتزاز خفيف على الأجهزة التي تدعمه. وفيه خيار «نبرة فقط» أو «بدون صوت»، وزر لتجربة الصوت قبل البدء.
	•	منع انطفاء الشاشة: يستخدم Screen Wake Lock عند توفره، ومكتبة NoSleep.js كحل احتياطي للمتصفحات الأخرى.
	•	تصميم هادئ: واجهة عربية من اليمين لليسار، ونمط فاتح وداكن تلقائيًا، وحركات ناعمة، وخط كبير يُقرأ من بعيد.
	•	ملف واحد بلا تثبيت: index.html فقط، بدون خادم ولا بناء.

طريقة الاستخدام

	1.	افتح الرابط في المتصفح على جوالك.
	2.	اختر الصلاة والإيقاع المناسب.
	3.	اضغط 🔔 جرّب الصوت للتأكد أن الصوت يعمل.
	4.	اضغط ابدأ الصلاة، وضع الجوال أمامك.

النشر على GitHub Pages

	1.	ارفع index.html إلى المستودع.
	2.	من Settings ← Pages اختر Deploy from a branch، والفرع main، والمجلد / (root)، ثم Save.
	3.	يظهر رابط الموقع بعد دقيقة أو دقيقتين.

التخصيص

كل المحتوى داخل index.html:

	•	الدالة build() تبني خطوات الصلاة (النصوص، الملاحظات، المدد بالثواني).
	•	المصفوفة FAT للفاتحة ومعانيها، وSUR للسور القصيرة.
	•	المتغيرات TAH وSAL للتشهد والصلاة الإبراهيمية.
	•	الألوان في متغيرات :root أعلى الملف.

ملاحظات

	•	الصيغ والوضعيات هي المتداولة عند أكثر أهل السنة، وقد تختلف بعض التفاصيل بحسب المذهب، وهي قابلة للتعديل من الدالة build().
	•	التطبيق معين على الحضور وليس بديلًا عن تعلّم الصلاة من أهل العلم.
	•	المدد ثابتة لكل خطوة، فالتطبيق لا يسمعك. إن احتجت وقتًا أطول فاختر إيقاعًا أبطأ أو أوقف مؤقتًا.
	•	جودة النطق الصوتي بالعربية تعتمد على الأصوات المثبتة في جهازك.
	•	الخطوط وNoSleep تُحمَّل من الإنترنت، فيلزم اتصال عند أول فتح.

الاعتمادات

تصميم وبرمجة عبدالعزيز الأمير.

🤍 لا تنسونا من صالح دعائكم.

English

Khushu Companion is a guided prayer web app that walks you step by step from the iqama to the taslim and the dhikr after prayer, with calm pacing that helps you stay present. Pick a prayer, press Start, place your phone on the floor in front of you, and it moves along on its own.

Features

	•	All five daily prayers (Fajr, Dhuhr, Asr, Maghrib, Isha) with the correct number of rak'ahs.
	•	Iqama to closing: iqama, opening takbir, opening supplication, isti'adha, Al-Fatiha, a short surah, ruku', rising, both sujud, sitting between them, both tashahhuds, the Ibrahimiyya salawat, taslim, then post-prayer istighfar.
	•	Extra detail in the first rak'ah: Al-Fatiha is shown verse by verse, each with a short reflection on its meaning.
	•	Posture guidance: every step includes a note on body, gaze, hands and calmness, plus a small posture illustration (standing, ruku', sujud, sitting).
	•	Auto mode: steps advance on a timer with three paces (calm, slow, very slow). Manual controls (previous, next, pause) are always available.
	•	Gentle audio cues: a soft chime at each transition plus the spoken step name, with light vibration where supported. Options for chime only or no sound, and a test button before you begin.
	•	Screen stays awake: uses the Screen Wake Lock API when available, with NoSleep.js as a cross-browser fallback.
	•	Calm design: RTL Arabic interface, automatic light and dark themes, soft animations, and large text readable from a distance.
	•	Single file, zero setup: just index.html. No server, no build step.

How to use

	1.	Open the link in your phone's browser.
	2.	Choose the prayer and pace.
	3.	Tap 🔔 Test sound to make sure audio works.
	4.	Tap Start, and place the phone in front of you.

Deploy on GitHub Pages

	1.	Upload index.html to the repository.
	2.	Go to Settings → Pages, choose Deploy from a branch, branch main, folder / (root), then Save.
	3.	Your site URL appears after a minute or two.

Customization

Everything lives in index.html:

	•	build() generates the prayer steps (text, notes, durations in seconds).
	•	FAT holds Al-Fatiha with its reflections, and SUR holds the short surahs.
	•	TAH and SAL hold the tashahhud and salawat texts.
	•	Colors are CSS variables in :root near the top of the file.

Notes

	•	The wording and postures follow the commonly used Sunni format. Details can differ by school of thought, and you can adjust them in build().
	•	This app is an aid for presence, not a substitute for learning prayer from qualified teachers.
	•	Step durations are fixed, as the app does not listen to you. Choose a slower pace or pause if you need more time.
	•	Arabic speech quality depends on the voices installed on your device.
	•	Fonts and NoSleep load from the internet, so a connection is needed on first open.

Credits

Designed and developed by Abdulazeez Al-Ameer.

🤍 Please keep us in your prayers.

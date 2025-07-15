<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>קריירה בהנדסת בניין</title>
    <!-- טעינת Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- טעינת Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Assistant:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        /* הוספת הפונט Assistant לכל האתר */
        html {
            scroll-behavior: smooth;
        }
        body {
            font-family: 'Assistant', sans-serif;
        }
        /* הסרת החצים של שדה מסוג חיפוש בדפדפנים מסוימים */
        input[type="search"]::-webkit-search-decoration,
        input[type="search"]::-webkit-search-cancel-button,
        input[type="search"]::-webkit-search-results-button,
        input[type="search"]::-webkit-search-results-decoration {
            -webkit-appearance: none;
        }
        .carousel-track {
            transition: transform 0.5s ease-in-out;
        }
        /* קרוסלת לוגואים */
        .logos-track {
            display: flex;
            animation: scroll 40s linear infinite;
        }
        @keyframes scroll {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }
        /* הסתרת פס הגלילה של הטאבים */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;  /* IE and Edge */
            scrollbar-width: none;  /* Firefox */
        }
    </style>
</head>
<body class="bg-gray-100">

    <!-- Header Container -->
    <header class="bg-[#2d3748] shadow-md">
        <!-- Top Navigation Bar -->
        <div class="container mx-auto px-4">
            <div class="flex justify-between items-center py-2 text-white text-sm">
                <!-- Left Side: Auth and Employer Links -->
                <div class="flex items-center space-x-2 md:space-x-4 rtl:space-x-reverse">
                    <a href="#" class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-2 px-3 md:px-4 rounded-md transition duration-300 text-xs md:text-sm">פרסם/י מודעה</a>
                    <a href="#" class="hover:text-orange-400 transition duration-300 text-xs md:text-sm">כניסה</a>
                    <div class="border-l h-4 border-gray-500"></div>
                    <a href="#" class="hover:text-orange-400 transition duration-300 text-xs md:text-sm">הרשמה</a>
                </div>

                <!-- Right Side: Logo and Main Nav -->
                <div class="flex items-center space-x-3 md:space-x-6 rtl:space-x-reverse">
                    <!-- Logo -->
                    <a href="#" class="text-xl md:text-2xl font-bold text-white">AllJobs</a>
                    <!-- Main Navigation Links -->
                    <nav class="hidden md:flex items-center space-x-5 rtl:space-x-reverse font-semibold">
                        <a href="#" class="hover:text-orange-400 transition duration-300">קונים חיים</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">ניהול קריירה</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">שכר</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">דרושים</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">כל החברות</a>
                        <a href="#" class="hover:text-orange-400 transition duration-300">שירותים נוספים VIP</a>
                    </nav>
                </div>
            </div>
        </div>

        <!-- Title Section with Background Image -->
        <div class="relative bg-cover bg-center py-16 md:py-20" style="background-image: url('https://thefieldengineer.com/wp-content/uploads/2023/09/Woman-and-man-Civil-Engineers.png');">
            <!-- Overlay for better text readability -->
            <div class="absolute inset-0 bg-[#2d3748] opacity-60"></div>
            
            <!-- Content -->
            <div class="relative container mx-auto px-4 text-center">
                <h1 class="text-3xl md:text-5xl font-bold text-white mb-6">קריירה בהנדסת בניין</h1>
                <!-- Tabs Navigation -->
                <div class="max-w-full mx-auto bg-white/10 backdrop-blur-sm rounded-lg shadow-lg mb-6">
                    <div class="flex items-center justify-start md:justify-center overflow-x-auto whitespace-nowrap p-2 no-scrollbar">
                        <a href="#jobs" class="flex-shrink-0 text-white bg-orange-500/80 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">משרות</a>
                        <a href="#how-to-start" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">איך נכנסים לתחום</a>
                        <a href="#roles" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">תפקידים</a>
                        <a href="#salary" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">שכר</a>
                        <a href="#seniors" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">בכירים</a>
                        <a href="#hiring-companies" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">חברות מגייסות</a>
                        <a href="#follow-worthy" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">כדאי לעקוב</a>
                        <a href="#engineer-stories" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">סיפורי מהנדסים</a>
                        <a href="#guides" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">מדריכים</a>
                        <a href="#faq" class="flex-shrink-0 text-white hover:bg-white/20 font-bold py-2 px-4 mx-1 rounded-md transition duration-300 text-sm">שאלות נפוצות</a>
                    </div>
                </div>
                <!-- Search Box -->
                <div class="max-w-4xl mx-auto bg-white rounded-lg p-2 md:p-3 shadow-lg">
                    <form class="flex flex-col md:flex-row gap-2 items-center">
                        <div class="w-full md:flex-1 flex items-center border-b-2 md:border-b-0 md:border-r-2 rtl:md:border-r-0 rtl:md:border-l-2 border-gray-200 pr-2 rtl:pr-0 rtl:pl-2">
                             <input type="search" value="הנדסת בניין" class="w-full p-2 text-gray-600 bg-transparent focus:outline-none text-right" placeholder="תחום, התמחות, משרה...">
                        </div>
                        <div class="w-full md:flex-1 flex items-center">
                             <input type="text" placeholder="איפה תרצו לעבוד?" class="w-full p-2 text-gray-600 bg-transparent focus:outline-none placeholder-gray-400 text-right">
                        </div>
                        <div class="w-full md:w-auto">
                            <button type="submit" class="w-full bg-orange-500 hover:bg-orange-600 text-white font-bold py-3 px-6 rounded-lg flex items-center justify-center transition duration-300">
                                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto p-4 md:p-8">
        
        <!-- Sections container -->
        <div class="space-y-12 md:space-y-16">

            <section id="jobs" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">משרות חמות בהנדסת בניין</h2><div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6"><!-- Job Cards... --><div class="bg-white border border-gray-200 rounded-lg shadow-lg p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col"><div class="flex-grow"><h3 class="text-xl font-bold text-gray-900 mb-2">מהנדס/ת ביצוע</h3><p class="text-md text-gray-700 font-semibold mb-1">דניה סיבוס</p><p class="text-sm text-gray-500 mb-4">אזור המרכז</p><p class="text-gray-600">ניהול ופיקוח על עבודות בנייה באתר, אחריות על עמידה בלוחות זמנים, תקציב ואיכות. ניסיון בביצוע - יתרון.</p></div><button class="mt-4 w-full bg-orange-500 text-white py-2 rounded-lg hover:bg-orange-600 transition-colors">הגש מועמדות</button></div><div class="bg-white border border-gray-200 rounded-lg shadow-lg p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col"><div class="flex-grow"><h3 class="text-xl font-bold text-gray-900 mb-2">מנהל/ת פרויקטים</h3><p class="text-md text-gray-700 font-semibold mb-1">שיכון ובינוי</p><p class="text-sm text-gray-500 mb-4">תל אביב-יפו</p><p class="text-gray-600">אחריות כוללת על ניהול פרויקטי בנייה למגורים משלב התכנון ועד למסירה. ניסיון בניהול פרויקטים חובה.</p></div><button class="mt-4 w-full bg-orange-500 text-white py-2 rounded-lg hover:bg-orange-600 transition-colors">הגש מועמדות</button></div><div class="bg-white border border-gray-200 rounded-lg shadow-lg p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col"><div class="flex-grow"><h3 class="text-xl font-bold text-gray-900 mb-2">מהנדס/ת קונסטרוקציה</h3><p class="text-md text-gray-700 font-semibold mb-1">משרד מהנדסים מוביל</p><p class="text-sm text-gray-500 mb-4">חיפה</p><p class="text-gray-600">תכנון שלדי מבנים, חישובים סטטיים והכנת תוכניות קונסטרוקציה. נדרש ניסיון בתכנון מבני בטון ופלדה.</p></div><button class="mt-4 w-full bg-orange-500 text-white py-2 rounded-lg hover:bg-orange-600 transition-colors">הגש מועמדות</button></div></div></section>

            <section id="how-to-start" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">איך נכנסים לתחום?</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto"><p class="text-gray-700 leading-relaxed mb-4">הדרך לקריירה בהנדסת בניין מתחילה בלימודי תואר ראשון (B.Sc) במוסד אקדמי מוכר, כמו <b class="text-orange-500">הטכניון</b>, <b class="text-orange-500">אוניברסיטת תל אביב</b> או <b class="text-orange-500">אוניברסיטת בן-גוריון</b>. לאחר סיום הלימודים, יש לעבור תהליך רישוי בפנקס המהנדסים והאדריכלים. מהנדסים רבים מתחילים את דרכם כמהנדסי ביצוע באתר בנייה כדי לצבור ניסיון מעשי, ומשם מתקדמים לתפקידי ניהול או תכנון.</p><div class="text-center mt-6"><a href="#" class="font-bold text-orange-500 hover:text-orange-600">עוד על כניסה לתחום הנדסת הבניין ←</a></div></div></section>

            <section id="roles" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">תפקידים והתמחויות</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto"><ul class="list-disc list-inside space-y-2 text-gray-700"><li><b>הנדסת מבנים (קונסטרוקציה):</b> תכנון שלד המבנה ועמידותו בעומסים.</li><li><b>ניהול הבנייה:</b> ניהול פרויקטים, לוחות זמנים, תקציבים וכוח אדם.</li><li><b>הנדסת תחבורה:</b> תכנון כבישים, מחלפים ומערכות הסעת המונים.</li><li><b>הנדסת מים וסביבה:</b> תכנון מערכות מים, ביוב וטיפול בפסולת.</li><li><b>הנדסה גיאוטכנית:</b> התמחות בקרקע וביסוס מבנים.</li><li><b>הנדסת חומרים:</b> מחקר ופיתוח של חומרי בנייה חדשים.</li></ul><div class="text-center mt-6"><a href="#" class="font-bold text-orange-500 hover:text-orange-600">עוד על תפקידים והתמחויות בהנדסת בניין ←</a></div></div></section>

            <section id="salary" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">שכר</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto"><div class="flex flex-col md:flex-row gap-8 items-center"><div class="flex-1"><p class="text-gray-700 leading-relaxed">שכר מהנדסי בניין נחשב גבוה יחסית וצומח עם הניסיון. מהנדס מתחיל יכול להרוויח בין 12,000 ל-16,000 ש"ח. לאחר 3-5 שנות ניסיון, השכר עולה לטווח של 18,000-25,000 ש"ח. מנהלי פרויקטים ומהנדסים בכירים יכולים להגיע למשכורות של 30,000 ש"ח ומעלה, בהתאם לגודל הפרויקט והחברה.</p></div><div class="flex-1 w-full max-w-xs mx-auto"><canvas id="salaryChart"></canvas></div></div><div class="text-center mt-6"><a href="#" class="font-bold text-orange-500 hover:text-orange-600">עוד על שכר של מהנדסי בניין ←</a></div></div></section>
            
            <section id="seniors" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">בכירים בתעשייה</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto"><div class="flex flex-col md:flex-row gap-8 items-center"><div class="flex-1"><p class="text-gray-700 leading-relaxed">התקדמות לתפקידים בכירים בענף הבנייה פותחת אפשרויות ניהוליות רחבות. תפקידים אלו דורשים ניסיון מוכח בניהול פרויקטים מורכבים, יכולת ניהול צוותים גדולים והבנה עסקית ומשפטית. התפקידים הנפוצים כוללים מנהל פרויקטים בכיר, מנהל אזור, מהנדס ראשי של חברה ועד לתפקידי סמנכ"ל הנדסה ומנכ"ל בחברות בנייה ויזמות.</p></div><div class="flex-1 w-full max-w-xs mx-auto"><canvas id="seniorsChart"></canvas></div></div><div class="text-center mt-6"><a href="#" class="font-bold text-orange-500 hover:text-orange-600">עוד על תפקידי בכירים בהנדסת בניין ←</a></div></div></section>

            <section id="hiring-companies" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">חברות מובילות שמגייסות</h2><div class="bg-white p-8 rounded-lg shadow-lg w-full overflow-hidden"><div id="logos-container" class="logos-container"><div class="logos-track"><!-- Logos will be duplicated by JS for smooth infinite scroll --><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/003366/ffffff?text=שיכון+ובינוי" alt="לוגו שיכון ובינוי"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/d92231/ffffff?text=דניה+סיבוס" alt="לוגו דניה סיבוס"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/00a4e4/ffffff?text=אשטרום" alt="לוגו אשטרום"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/005a99/ffffff?text=אלקטרה+בנייה" alt="לוגו אלקטרה בנייה"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/f37021/ffffff?text=אפריקה+ישראל" alt="לוגו אפריקה ישראל"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/009639/ffffff?text=תדהר" alt="לוגו תדהר"></div><div class="flex-shrink-0 w-40 mx-8 flex items-center justify-center"><img src="https://placehold.co/150x80/8c8c8c/ffffff?text=נתיבי+ישראל" alt="לוגו נתיבי ישראל"></div></div></div></div></section>

            <section id="follow-worthy" class="pt-10 -mt-10">
                <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">כדאי לעקוב</h2>
                <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- LinkedIn -->
                    <div class="bg-white p-6 rounded-lg shadow-lg">
                        <h3 class="text-xl font-bold mb-4 text-center">לינקדאין</h3>
                        <div class="space-y-4">
                            <a href="#" class="flex items-center gap-4 hover:bg-gray-50 p-2 rounded-lg">
                                <img src="https://placehold.co/50x50/e2e8f0/2d3748?text=IE" alt="איגוד המהנדסים" class="w-12 h-12 rounded-full">
                                <div>
                                    <p class="font-bold">איגוד המהנדסים לבנייה</p>
                                    <p class="text-sm text-gray-500">עדכונים וחדשות מהתעשייה</p>
                                </div>
                            </a>
                            <a href="#" class="flex items-center gap-4 hover:bg-gray-50 p-2 rounded-lg">
                                <img src="https://placehold.co/50x50/e2e8f0/2d3748?text=ND" alt="נדלניסט" class="w-12 h-12 rounded-full">
                                <div>
                                    <p class="font-bold">TheMarker נדל"ן</p>
                                    <p class="text-sm text-gray-500">כתבות ומאמרים על שוק הנדל"ן</p>
                                </div>
                            </a>
                        </div>
                    </div>
                    <!-- Video -->
                    <div class="bg-white p-6 rounded-lg shadow-lg">
                        <h3 class="text-xl font-bold mb-4 text-center">וידאו</h3>
                        <div class="aspect-w-16 aspect-h-9">
                            <iframe src="https://www.youtube.com/embed/watch?v=G13zQ-ILGg4&list=PL5F52452F7A630C1C" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="rounded-lg w-full h-48"></iframe>
                        </div>
                        <p class="font-bold mt-2 text-center">ערוץ The B1M</p>
                    </div>
                    <!-- Podcasts -->
                    <div class="bg-white p-6 rounded-lg shadow-lg">
                        <h3 class="text-xl font-bold mb-4 text-center">פודקאסטים</h3>
                        <div class="space-y-4">
                            <a href="#" class="block hover:bg-gray-50 p-3 rounded-lg">
                                <p class="font-bold">הפודקאסט של התאחדות הקבלנים</p>
                                <p class="text-sm text-gray-500">שיחות על אתגרי הענף</p>
                            </a>
                            <a href="#" class="block hover:bg-gray-50 p-3 rounded-lg">
                                <p class="font-bold">Civil Engineering Podcast</p>
                                <p class="text-sm text-gray-500">ראיונות עם מהנדסים מובילים בעולם</p>
                            </a>
                        </div>
                    </div>
                </div>
            </section>

            <section id="engineer-stories" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">סיפורים של מהנדסים</h2><div class="max-w-4xl mx-auto relative"><div id="carousel-container" class="overflow-hidden"><div id="carousel-track" class="carousel-track flex"><!-- Carousel Items --><a href="#" class="carousel-item flex-shrink-0 w-full block"><div class="bg-white p-8 text-center rounded-lg shadow-lg hover:shadow-xl transition-shadow"><img src="https://placehold.co/150x150/a0aec0/ffffff?text=ישראל+דוד" alt="ישראל דוד" class="w-24 h-24 rounded-full mx-auto mb-4 shadow-md"><h3 class="font-bold text-xl">ישראל דוד</h3><p class="text-gray-500 mb-2">מנהל פרויקט גשר יהודית</p><p class="text-gray-700">"להרים קונסטרוקציית פלדה במשקל מאות טונות מעל נתיבי איילון בלילה אחד - זה אתגר הנדסי שאין שני לו."</p><span class="mt-4 inline-block font-semibold text-orange-500">קרא את הסיפור המלא ←</span></div></a><a href="#" class="carousel-item flex-shrink-0 w-full block"><div class="bg-white p-8 text-center rounded-lg shadow-lg hover:shadow-xl transition-shadow"><img src="https://placehold.co/150x150/a0aec0/ffffff?text=מיכל+כהן" alt="מיכל כהן" class="w-24 h-24 rounded-full mx-auto mb-4 shadow-md"><h3 class="font-bold text-xl">מיכל כהן</h3><p class="text-gray-500 mb-2">מהנדסת מבנים</p><p class="text-gray-700">"הסיפוק הגדול ביותר הוא לראות תוכניות על הנייר הופכות למגדל מרשים. כל קו בשרטוט הוא החלטה עם אחריות עצומה."</p><span class="mt-4 inline-block font-semibold text-orange-500">קרא את הסיפור המלא ←</span></div></a><a href="#" class="carousel-item flex-shrink-0 w-full block"><div class="bg-white p-8 text-center rounded-lg shadow-lg hover:shadow-xl transition-shadow"><img src="https://placehold.co/150x150/a0aec0/ffffff?text=דני+לוי" alt="דני לוי" class="w-24 h-24 rounded-full mx-auto mb-4 shadow-md"><h3 class="font-bold text-xl">דני לוי</h3><p class="text-gray-500 mb-2">מהנדס הרכבת הקלה</p><p class="text-gray-700">"לתכנן מערכת הסעת המונים שתשנה את פני המטרופולין זה פרויקט של פעם בחיים. זו הנדסה שמשפיעה על מיליונים."</p><span class="mt-4 inline-block font-semibold text-orange-500">קרא את הסיפור המלא ←</span></div></a></div></div><button id="prevBtn" class="absolute top-1/2 left-0 -translate-y-1/2 bg-white/50 hover:bg-white/80 p-2 rounded-full shadow-md disabled:opacity-50 disabled:cursor-not-allowed"><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" /></svg></button><button id="nextBtn" class="absolute top-1/2 right-0 -translate-y-1/2 bg-white/50 hover:bg-white/80 p-2 rounded-full shadow-md disabled:opacity-50 disabled:cursor-not-allowed"><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg></button></div></section>

            <section id="guides" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">מדריכים וכתבות על הנדסת בניין</h2><div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8"><!-- Article Cards... --><div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300"><img src="https://placehold.co/600x400/e2e8f0/2d3748?text=טיפים+למהנדס" alt="תמונת מאמר" class="w-full h-48 object-cover"><div class="p-6"><h3 class="text-xl font-bold text-gray-900 mb-3">5 טיפים למהנדס המתחיל</h3><p class="text-gray-600 mb-4">איך לצלוח את השנה הראשונה באתר, ממה להיזהר ואיך לבנות מוניטין מקצועי מהרגע הראשון.</p><a href="#" class="font-semibold text-orange-500 hover:text-orange-600">קרא עוד ←</a></div></div><div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300"><img src="https://placehold.co/600x400/cbd5e0/2d3748?text=טכנולוגיות+בנייה" alt="תמונת מאמר" class="w-full h-48 object-cover"><div class="p-6"><h3 class="text-xl font-bold text-gray-900 mb-3">העתיד כבר כאן: טכנולוגיות בבנייה</h3><p class="text-gray-600 mb-4">מבנייה מודולרית ועד שימוש ברחפנים ו-BIM, הטכנולוגיות שמשנות את עולם הבנייה.</p><a href="#" class="font-semibold text-orange-500 hover:text-orange-600">קרא עוד ←</a></div></div><div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300"><img src="https://placehold.co/600x400/a0aec0/2d3748?text=בנייה+ירוקה" alt="תמונת מאמר" class="w-full h-48 object-cover"><div class="p-6"><h3 class="text-xl font-bold text-gray-900 mb-3">בנייה ירוקה: לא רק סיסמה</h3><p class="text-gray-600 mb-4">המדריך המלא לתכנון וביצוע פרויקטים ברי-קיימא העומדים בתקנים המחמירים ביותר.</p><a href="#" class="font-semibold text-orange-500 hover:text-orange-600">קרא עוד ←</a></div></div></div></section>
            
            <section id="faq" class="pt-10 -mt-10"><h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 text-center">שאלות נפוצות</h2><div class="bg-white p-6 md:p-8 rounded-lg shadow-lg max-w-4xl mx-auto space-y-4"><details class="border-b pb-4"><summary class="font-bold text-lg text-gray-800 cursor-pointer">מה ההבדל בין מהנדס ביצוע למהנדס תכנון?</summary><p class="text-gray-700 mt-2"><b>מהנדס תכנון (קונסטרוקטור)</b> עובד במשרד ואחראי על תכנון שלד המבנה וחישוביו. <b>מהנדס ביצוע</b> עובד באתר הבנייה ואחראי על הפיכת התוכניות למציאות, ניהול העבודה בשטח ועמידה בלו"ז ובתקציב.</p></details><details class="border-b pb-4"><summary class="font-bold text-lg text-gray-800 cursor-pointer">האם חייבים רישיון כדי לעבוד כמהנדס בניין?</summary><p class="text-gray-700 mt-2">כדי לעסוק בתכנון מבנים ולחתום על תוכניות (תפקידי קונסטרוקטור), חובה להיות רשום ורשוי בפנקס המהנדסים והאדריכלים. לתפקידי ביצוע וניהול רבים, מספיק להיות רשום כמהנדס, אך רישיון מהווה יתרון משמעותי.</p></details></div></section>

        </div>
    </main>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Carousel Logic
            const track = document.getElementById('carousel-track');
            if (track) {
                const items = track.querySelectorAll('.carousel-item');
                const prevBtn = document.getElementById('prevBtn');
                const nextBtn = document.getElementById('nextBtn');
                
                let currentIndex = 0;
                const totalItems = items.length;

                function updateCarousel() {
                    track.style.transform = `translateX(${currentIndex * 100}%)`;
                    if (prevBtn) prevBtn.disabled = currentIndex === 0;
                    if (nextBtn) nextBtn.disabled = currentIndex <= -(totalItems - 1);
                }

                if (nextBtn) nextBtn.addEventListener('click', () => {
                    if (currentIndex > -(totalItems - 1)) {
                        currentIndex--;
                        updateCarousel();
                    }
                });

                if (prevBtn) prevBtn.addEventListener('click', () => {
                    if (currentIndex < 0) {
                        currentIndex++;
                        updateCarousel();
                    }
                });
                
                updateCarousel();
            }

            // Logos Carousel
            const logosTrack = document.querySelector('.logos-track');
            if (logosTrack) {
                const logos = logosTrack.innerHTML;
                logosTrack.innerHTML += logos; // Duplicate logos for infinite scroll effect
            }

            // Salary Chart
            const salaryCtx = document.getElementById('salaryChart');
            if (salaryCtx) {
                new Chart(salaryCtx, {
                    type: 'pie',
                    data: {
                        labels: ['מהנדס/ת מתחיל/ה (עד 3 שנים)', 'מהנדס/ת מנוסה (3-7 שנים)', 'מהנדס/ת בכיר/ה (7+ שנים)'],
                        datasets: [{
                            label: 'התפלגות שכר',
                            data: [30, 40, 30],
                            backgroundColor: ['#f6ad55', '#ed8936', '#dd6b20'],
                            hoverOffset: 4
                        }]
                    },
                    options: { responsive: true, plugins: { legend: { position: 'top', labels: { font: { family: 'Assistant' } } } } }
                });
            }
            
            // Seniors Chart
            const seniorsCtx = document.getElementById('seniorsChart');
            if (seniorsCtx) {
                new Chart(seniorsCtx, {
                    type: 'pie',
                    data: {
                        labels: ['מנהל/ת פרויקטים בכיר/ה', 'מהנדס/ת ראשי/ת', 'סמנכ"ל/ית הנדסה'],
                        datasets: [{
                            label: 'התפלגות תפקידי בכירים',
                            data: [50, 30, 20],
                            backgroundColor: ['#48bb78', '#38a169', '#2f855a'],
                            hoverOffset: 4
                        }]
                    },
                     options: { responsive: true, plugins: { legend: { position: 'top', labels: { font: { family: 'Assistant' } } } } }
                });
            }
        });
    </script>

</body>
</html>

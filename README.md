<!--
  The Art of Getting Lost: profile README for @EnesKaraca44.
  Every image in /assets is a self-contained SVG (lettering is outlined, no external fonts or images),
  so the page looks the same on every device. Animations respect prefers-reduced-motion.
-->

<p align="center">
  <img src="assets/hero-atlas.svg" width="100%" alt="The Art of Getting Lost. An antique atlas with a dotted route crossing Europe to Anatolia and arcing on to Japan. Enes Karaca, mobile and backend developer, curious about data and machine learning.">
</p>

<h2 align="center"><img src="assets/banners/field-notes.svg" width="100%" alt="Field notes"></h2>

I'm Enes, a developer from Türkiye working across three territories: native Android and Flutter apps, backends in ASP.NET Core and Flask, and data science with machine learning. I learn the way travellers do, by heading somewhere unfamiliar and building my way through it. So far that has meant a phone camera that coaches workout form, a live photo wall for weddings, and a graduation thesis that forecasts and optimises BIST&nbsp;30 portfolios.

I take on freelance projects through [Upwork](https://www.upwork.com/freelancers/~0143bae00c47e48a6a), and I'm always glad to hear about a new route worth exploring.

<p align="center">
  <img src="assets/stamps/turkey.svg" width="14%" alt="Stamp: Anatolia, a tulip">
  <img src="assets/stamps/italy.svg" width="14%" alt="Stamp: Italia, aqueduct arches">
  <img src="assets/stamps/japan.svg" width="14%" alt="Stamp: Iaponia, a torii gate">
  <img src="assets/stamps/france.svg" width="14%" alt="Stamp: Gallia, a café cup">
  <img src="assets/stamps/hungary.svg" width="14%" alt="Stamp: Hungaria, a chain bridge over the Danube">
  <img src="assets/stamps/united-kingdom.svg" width="14%" alt="Stamp: Britannia, a telephone box">
</p>
<p align="center"><sub><i>Places to explore, ideas to build.</i></sub></p>

<h2 align="center"><img src="assets/banners/toolkit.svg" width="100%" alt="The explorer's kit"></h2>

<p align="center">
  <img src="assets/toolkit.svg" width="100%" alt="Technologies, grouped like a map legend. Mobile: Kotlin, Flutter, Android Jetpack, Dart, CameraX and ML Kit, Bloc and Riverpod. Backend and web: C#, Flask, ASP.NET Core, Entity Framework, SignalR, React and TypeScript. Data science and ML: Python, scikit-learn, pandas and NumPy, TensorFlow and Keras, ARIMA and GARCH, XGBoost and CatBoost. Storage and cloud: SQL Server, Firebase, PostgreSQL, Cloud Functions, SQLite, Gemini API.">
</p>

<h2 align="center"><img src="assets/banners/expeditions.svg" width="100%" alt="Featured expeditions"></h2>

<a href="https://github.com/EnesKaraca44/bist30-portfoy-optimizasyonu"><img src="assets/expeditions/portfoyoptim.svg" width="100%" alt="PortföyOptim drawn as a route map: market data, features, forecasts, blending, portfolio."></a>

### [PortföyOptim: BIST 30 portfolio optimisation](https://github.com/EnesKaraca44/bist30-portfoy-optimizasyonu)

My graduation thesis: a Flask web application that estimates return and risk for every BIST&nbsp;30 stock and proposes portfolios for low, medium and high risk profiles. A batch pipeline combines auto-ARIMA forecasts (fed by 51 technical indicators and macro signals such as USD/TRY, Brent oil and the central bank policy rate), GARCH(1,1) volatility, Black–Litterman views and a per-stock LSTM ensemble, then Monte Carlo simulation searches for the portfolio weights. The interface compares classic Modern Portfolio Theory with the ML portfolio, tracks forecast accuracy and runs a weekly user-versus-AI leaderboard. The repository includes a unittest suite and a one-year backtest.

<sub>Built with Python, Flask, TensorFlow and Keras, pmdarima, arch, scikit-learn, Plotly and SQLite.</sub>

<p align="center"><img src="assets/section-divider.svg" width="72%" alt=""></p>

<a href="https://github.com/EnesKaraca44/ArFitness"><img src="assets/expeditions/arfitness.svg" width="100%" alt="ArFitness drawn as a route map: camera, pose, analyzer, logbook, with two app screenshots pinned like photographs."></a>

### [ArFitness: an on-device AI workout coach](https://github.com/EnesKaraca44/ArFitness)

An Android app that turns the phone camera into a form coach. CameraX frames go to ML Kit Pose Detection, a custom overlay draws the detected skeleton, and a dedicated analyzer for each of 15 exercises reads joint angles to count reps, track movement phases and flag common form mistakes. Squats and lunges are also matched against reference movements with dynamic time warping. Workouts, form scores and history are stored on the device with Room, and camera frames are processed locally rather than uploaded.

<sub>Built with Kotlin, MVVM, Hilt, CameraX, ML Kit Pose Detection, Room, Coroutines and Flow, and MPAndroidChart.</sub>

<p align="center"><img src="assets/section-divider.svg" width="72%" alt=""></p>

<a href="https://github.com/EnesKaraca44/KarWed"><img src="assets/expeditions/karwed.svg" width="100%" alt="KarWed drawn as a route map: guest, upload, moderation, big screen."></a>

### [KarWed: a live photo wall for weddings and events](https://github.com/EnesKaraca44/KarWed)

Guests scan a QR code at their table and upload photos and messages from the browser, with no app to install. The host approves each post in a moderation queue, and approved posts appear on the venue's big-screen slideshow in real time through SignalR, while a second hub keeps the admin panel's pending count live. The platform also covers ASP.NET Core Identity with Google sign-in, plan tiers, venue branding and server-side image processing.

<sub>Built with C#, ASP.NET Core 8 MVC, SignalR, Entity Framework Core, SQL Server and ImageSharp.</sub>

<p align="center"><img src="assets/section-divider.svg" width="72%" alt=""></p>

<a href="https://github.com/EnesKaraca44/AI-Roast-Battle"><img src="assets/expeditions/kapak-olsun.svg" width="100%" alt="Kapak Olsun drawn as a route map: photo, gate, proxy, Gemini, showcase."></a>

### [Kapak Olsun (AI Roast Battle)](https://github.com/EnesKaraca44/AI-Roast-Battle)

A Flutter app that sends a photo to Google Gemini and returns a roast in the voice of a chosen character. Battle mode compares two photos and picks a winner, and a showcase feed lets people share and react to results. The Gemini key never ships with the app: every call goes through a Firebase Cloud Functions proxy that checks authentication and App Check tokens, validates the payload and enforces per-user rate limits stored in Firestore. Firestore and Storage security rules are tested against the emulator in CI, and the interface is localised in Turkish and English.

<sub>Built with Flutter, Dart, flutter_bloc (Cubit), get_it, Firebase (Auth, Firestore, Storage, Functions, App Check), the Gemini API and Hive.</sub>

<h2 align="center"><img src="assets/banners/discoveries.svg" width="100%" alt="Further discoveries"></h2>

### Mobile

- **[FilmSwipe](https://github.com/EnesKaraca44/FilmSwipe)**: settles "what do we watch tonight?" Friends join a room with a code and swipe through TMDB films, and a Cloud Function declares a match when everyone likes the same title. Also has quick duels with random players, in-room chat and an offline watchlist.<br><sub>Kotlin, Hilt, Retrofit, Firebase Realtime Database, Room, Lottie</sub>
- **[Zihin Bahçesi](https://github.com/EnesKaraca44/Zihin-Bahcesi)**: a digital-detox app in which completed focus tasks grow a virtual garden, with progress statistics.<br><sub>Flutter, Riverpod, Hive, go_router, fl_chart</sub>
- **[Modern Bütçe Takip](https://github.com/EnesKaraca44/Modern-butce-takip-uygulamasi)**: a budget tracker with categories, monthly summaries and charts.<br><sub>Flutter, Provider, sqflite, fl_chart</sub>

### Backend, web and desktop

- **[Kds](https://github.com/EnesKaraca44/Kds)**: a decision-support system for healthcare institutions, with Flask dashboards over SQL Server covering clinic traffic, treatment groups, stock, revenue, referrals, radiology and more.<br><sub>Python, Flask, pyodbc, pandas, Plotly, Waitress</sub>
- **[BerberOto](https://github.com/EnesKaraca44/BerberOto)**: appointment and customer management for barber shops, with SMS reminders sent by a background service.<br><sub>C#, ASP.NET Core 8, Entity Framework Core, SQLite</sub>
- **[YİMA Taahhüt ve İnşaat](https://github.com/EnesKaraca44/-YIMA-Taahhut-ve-Insaat)**: a corporate website for a civil-engineering contractor, with a filterable project gallery and all copy kept in a single content file.<br><sub>React 18, TypeScript, Vite, Tailwind CSS</sub>
- **[SOHAT](https://github.com/EnesKaraca44/SOHAT)**: a patient-tracking desktop system built as a school project in an N-tier architecture.<br><sub>C#, Windows Forms, PostgreSQL</sub>
- **[MiniERP](https://github.com/EnesKaraca44/MiniERP-StockManagement)**: stock and order management with critical-stock alerts and Excel export.<br><sub>C#, Windows Forms, SQL Server</sub>

### Data and AI

- **[Kripto](https://github.com/EnesKaraca44/Kripto)**: a crypto forecasting pipeline that pulls exchange data through ccxt and trains per-pair XGBoost, CatBoost and random-forest models, including 10th and 90th percentile quantile models, with a backtester.<br><sub>Python, ccxt, XGBoost, CatBoost, scikit-learn</sub>
- **[Perfume Review Analyzer](https://github.com/EnesKaraca44/perfume-review-analyzer)**: an NLP study on a synthetic set of Turkish perfume reviews, covering Turkish BERT sentiment, aspect-based sentiment, feature-importance ranking and K-Means consumer segments.<br><sub>Python, Hugging Face Transformers, NLTK, scikit-learn</sub>
- **[GÖRHÜK](https://github.com/EnesKaraca44/GORHUK)**: a desktop playground for more than 20 image-processing operations.<br><sub>Python, OpenCV, Tkinter</sub>
- **[Elite AI SDR Squad](https://github.com/EnesKaraca44/Elite-AI-SDR-Squad)**: a Flask app in which research, analysis, contact and outreach agents prepare sales briefs.<br><sub>Python, Flask, OpenAI, Gemini, Perplexity, Serper</sub>
- **[B2B Cold Outreach Engine](https://github.com/EnesKaraca44/B2B-Cold-Outreach-RevOps-Automation-Engine)**: a Streamlit tool for prospect discovery, contact-page scraping, Gemini-written opening lines and SMTP sending.<br><sub>Python, Streamlit, BeautifulSoup, Gemini API</sub>

<details>
<summary><b>Early coursework</b> (Kotlin and Flutter practice projects)</summary>
<br>

- **[YemekSepeti](https://github.com/EnesKaraca44/YemekSepeti)**: Kotlin bootcamp capstone, a food-ordering app with a cart backed by a REST API.
- **[NeYesemApp](https://github.com/EnesKaraca44/NeYesemApp)**: a recipe browser with categories, recipe details and favourites.
- **[Filmler-Uygulama-Calismasi](https://github.com/EnesKaraca44/Filmler-Uygulama-Calismasi)**: a film catalogue exercise.
- **[DOVIZ-APP](https://github.com/EnesKaraca44/DOVIZ-APP)**: a Flutter currency converter.
- **[4.odev-sayfalar-arasi-gecis](https://github.com/EnesKaraca44/4.odev-sayfalar-arasi-gecis)**, **[APP-ANA-SAYFA-TASARIM-CALISMASI](https://github.com/EnesKaraca44/APP-ANA-SAYFA-TASARIM-CALISMASI)** and **[KotlinFonksiyonOdevi](https://github.com/EnesKaraca44/KotlinFonksiyonOdevi)**: bootcamp exercises on navigation, layout and Kotlin functions.

</details>

<p align="center"><a href="https://github.com/EnesKaraca44?tab=repositories">Browse every repository</a></p>

<h2 align="center"><img src="assets/banners/logbook.svg" width="100%" alt="The logbook"></h2>

<!-- Live cards from github-readme-stats. Languages generated by Flutter's platform folders (C++, CMake, Swift, C, Objective-C) and markup (HTML, CSS) are hidden so the chart reflects hand-written code. -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=EnesKaraca44&show_icons=true&hide_rank=true&card_width=450&border_radius=0&bg_color=101410&title_color=B79A5B&text_color=E9DFC8&icon_color=A7654D&border_color=3A4231" width="49%" alt="GitHub statistics for EnesKaraca44">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EnesKaraca44&layout=compact&langs_count=6&card_width=450&hide=html,css,c%2B%2B,cmake,swift,c,objective-c&border_radius=0&bg_color=101410&title_color=B79A5B&text_color=E9DFC8&border_color=3A4231" width="49%" alt="Most used languages across EnesKaraca44's repositories">
</p>

<h2 align="center"><img src="assets/banners/correspondence.svg" width="100%" alt="Correspondence"></h2>

<p align="center">
  <a href="https://www.linkedin.com/in/enes-karaca-277655299/"><img src="assets/links/linkedin.svg" width="31%" alt="LinkedIn: career notes and contact"></a>
  <a href="https://www.upwork.com/freelancers/~0143bae00c47e48a6a"><img src="assets/links/upwork.svg" width="31%" alt="Upwork: freelance commissions"></a>
  <a href="https://github.com/EnesKaraca44?tab=repositories"><img src="assets/links/github.svg" width="31%" alt="GitHub: the complete archive"></a>
</p>

<p align="center">
  <img src="assets/closing-atlas.svg" width="100%" alt="A closing map of the north-western Pacific. The dotted route leaves Japan and runs off the edge of the map into a sea marked Mare incognitum. The journey continues. The next discovery starts with a new idea.">
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=EnesKaraca44&color=b79a5b&style=flat-square&label=visitors" alt="Profile visitor count">
</p>

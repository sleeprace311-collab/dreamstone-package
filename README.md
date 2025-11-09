# 💎 Packages Used in DreamStone App (v1.0.1)

These are the packages used in **dreamstone app** for **v1.0.1**, written on **9th November 2025**.

To visit each package's website, please visit `https://pub.dev/packages/{package-name}`

---

## 💾 Data & State Management

**isar**: it's a local database sdk to store user's **score related data**.

**shared_preferences**: a simple key-value local storage package to store data like theme and localization **preferences**.

**json_annotation**: used in my dart code to convert objects to **json** and back.

**Get**: it is used in **state management** and **routing**.

---

## ⏰ Notifications & Alarms

**Alarm** & **flutter_local_notifications** packages: they are used to trigger scheduled local **alarm notifications** based on the user's selected sleep and wake up time.

**timezone** & **flutter_timezone** packages: it handles **timezone conversion** to **ensure** notifications will trigger on time.

**permission_handler**: It is used to check **permission status** and ask for them (if missing), it is used to handle the **notification permission status**.

---

## ✨ UI/UX & Widgets

**duration_picker**: It's a **UI package** that provides a widget to pick **time durations**, I used it in the sleep settings and wake up settings pages.

**flutter_analog_clock**: It's a **UI widget** that provides an **analog clock** widget, I used it in the alarm page that shows when the notification (alarm) is triggered (as a full screen intent notification).

**showcaseview**: It is a **ui widget** that shows **on-screen instructions** to highlight key **features** of the app on the first visit.

**fluttertoast**: show brief **toast message** for quick feedbacks, I use it when the app fails to sync with play games service to inform the user.

**confetti**: It is a **ui widget** used to show **confetti design**, i use it in the pop-up **dialog** that displays as the user unlocks a new level or gets some score.

**super_tooltip**: A **ui widget** to show a small brief box (**tooltip**) above a certain widget to show its function, it is used in the wake up points and sleep points widgets that are displayed in home page (statistics page) **of** the app.

**flutter_spinkit**: It is a **ui widget** that provides custom animated **loading indicators**, it is the first thing displayed to the user while the score related data is synced **every time** the user opens the app.

**flutter_ripple_animation**: A **ui widget** that creates something like **pulse animation** around a certain widget, i used it around the analog clock widget displayed in the alarm screen (mentioned earlier).

**auto_size_text**: A widget to prevent text from overflowing by automatically adjusting its size depending on the screen width to keep the app's design neat.

---

## 🎨 Styling, Assets & Icons

**google_fonts**: It is a package that allows me to use fonts provided by google fonts website within my app, I use it to use **cairo font**.

**font_awesome_flutter**: It is a package that provides a wide variety of **icons** to use within my app, I used it in various pages and parts of my app.

**flutter_svg**: it allows the app to render **svg assets**, It is used to display the **stones graphics** (that expresses the score).

**icon_decoration**: It makes me able to customize the icons used within my app, I use it to add borders for some icon and add **gradient** colors in various parts.

---

## 🔗 External Integrations

**google_mobile_ads**: It is used to integrate with **google admob** to show **advertisements** in the app.

**games_services**: It is used to integrate with **google play games service**, I use it to **synchronize** the user's score related data (that is stored locally first) and take advantage of the **achievements** **feature**.

**url_launcher**: It is a package that allows the app to redirect users **to** **external links**, is is used in "**terms of service**", "**privacy policy**" & "**report a problem**" options which can be found in settings page.

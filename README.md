# 🚀 Wykład: Rok w DevOpsie – migracje, automatyzacje i doświadczenia z życia wzięte

## 🧭 1. Wprowadzenie: co działo się przez ostatni rok

Ten wykład to nie podręcznikowa teoria, ale praktyczny przegląd mojego ostatniego roku w świecie DevOps – z perspektywy realnych zadań, migracji i automatyzacji, które prowadziłem w firmie **S&P Global**. Opowiem Wam:

➡️ Co zastałem  
🔧 Co zmieniłem  
📚 Czego się nauczyłem  
❌ Czego bym nie powtórzył 😄

---

## 🛠️ 2. Co zastałem – stan CI/CD, narzędzia, problemy

- 🏗️ Systemy buildujące oparte o **TeamCity**
- 🚀 Deploymenty zarządzane przez **Octopus Deploy**
- 📦 Lokalny serwer feedów z paczkami **NuGet** i **npm**
- 🧩 Brak spójności w procesach buildowania i publikowania artefaktów
- 🖐️ Wdrożenia częściowo ręczne, mało elastyczne, zależne od wielu systemów

---

## 🔄 3. Co zmieniłem – usprawnienia, migracje, automatyzacje

- 🔁 **Migracja buildów** z TeamCity do **Azure Pipelines** (projekty web, frontend, baza danych)
- 🎯 **Przeniesienie artefaktów** (NuGet, npm) z lokalnych feedów do **Artifactory**
- 🧑‍💼 **Administracja Octopus Deploy** – zarządzanie rolloutami aplikacji
- 💸 **Migracja do GitHub Actions** – oszczędność kosztów + większa kontrola
- 🐳 Publikacja paczek do **GHCR** przez Azure Pipelines
- ☁️ Deploymenty do środowiska **AWS Cloud** – CI/CD full-stack
- 🧩 Budowa własnych **workflowów w GitHub Actions** od zera
- 🧰 Tworzenie **frameworka do migracji repozytoriów i zespołów** z Azure do GitHub

---

## 🧠 4. Czego się nauczyłem – kompetencje techniczne i miękkie

🔧 **Techniczne:**
- YAML masterclass: **Azure Pipelines**, **GitHub Actions**
- Praca z: **Artifactory**, **GHCR**, **NuGet**, **npm**
- Integracje CI/CD z **AWS** (EC2, S3, ECR, etc.)
- Migracje infrastruktury i repozytoriów

💬 **Miękkie:**
- Praca z wieloma zespołami (dev, QA, sec, PM)
- Dokumentowanie procesów migracyjnych
- Tłumaczenie DevOpsu na „ludzki język” 😄

---

## 🧪 4a. Technologie i języki, z którymi pracowałem

W ciągu tego roku miałem okazję pracować z różnorodnym zestawem technologii i języków skryptowych wykorzystywanych w automatyzacji i utrzymaniu procesów DevOps:

📝 **YAML** – serce każdego pipeline’a, używany do definiowania workflowów w GitHub Actions i Azure Pipelines  
🐚 **Bash** – automatyzacja zadań systemowych, skrypty uruchamiane lokalnie i w CI/CD  
🐪 **Perl** / 💎 **Ruby** – starsze skrypty wspierające procesy migracyjne lub monitoring  
⚙️ **C# Script (.csx)** – wykorzystywane w Octopus Deploy i przy budowaniu komponentów .NET  
🌍 **Terraform** – definiowanie infrastruktury jako kod, głównie pod środowiska AWS  
🥒 **Pickle** – lekkie DSL (domain-specific language) do konfiguracji starszych komponentów

To doświadczenie pozwoliło mi płynnie poruszać się między różnymi stylami automatyzacji – od nowoczesnych narzędzi DevOpsowych po starsze, ale wciąż działające rozwiązania.

## ⚠️ 5. Z czym było najtrudniej – fuckupy i lekcje

- 🔄 Rozbieżności w konfiguracjach pipeline’ów – brak standardów
- 📉 Braki w dokumentacji historycznej – „to działa, ale nie wiadomo dlaczego”
- 🧨 Niespodzianki przy migracjach: tokeny, taski, dostępności
- 🔄 Komunikacja: każdy zespół mówi „swoim językiem”

---

## 💡 6. Wnioski i refleksje

- 🛠️ Automatyzacja to nie tylko skrypty – to też komunikacja i dokumentacja
- 🚚 Migracje to świetna okazja, by ogarnąć procesy od A do Z
- 🧯 Dobrze zrobione CI/CD = ratunek dla projektu
- 🤯 GitHub Actions = moc + pole minowe 😅

---

## 🎓 7. Q&A + bonusowe tipy dla DevOpsujących studentów

💬 **Tipy:**
- 🧾 Naucz się czytać cudzy YAML – to skill premium
- 🏷️ Dbaj o wersjonowanie i opisy artefaktów
- 📘 Dokumentuj nawet małe zmiany – za miesiąc nie będziesz pamiętać
- 🤖 Automatyzuj z głową: najpierw zrozum, potem pisz

**Dzięki za uwagę – pytania?** 🎤


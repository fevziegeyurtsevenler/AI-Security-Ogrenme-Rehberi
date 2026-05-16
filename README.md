<p align="center">
  <a href="https://altaysec.com.tr">
    <img src="https://altaysec.com.tr/logo.jpg" alt="AltaySec — Türkiye'nin İlk Yapay Zeka Güvenliği Şirketi" width="120">
  </a>
</p>

<p align="center">
  <strong><a href="https://altaysec.com.tr">AltaySec</a></strong> — Türkiye'nin İlk Yapay Zeka Güvenliği Şirketi<br>
  <sub>Kurucu &amp; Yazar: <a href="https://altaysec.com.tr/hakkimizda.html">Fevzi Ege Yurtsevenler</a> · Yapay Zeka Güvenliği Araştırmacısı</sub>
</p>

<p align="center">
  <a href="https://altaysec.com.tr"><img src="https://img.shields.io/badge/web-altaysec.com.tr-8b5cf6"></a>
  <a href="https://ai.altaysec.com.tr"><img src="https://img.shields.io/badge/Akademi-LLM%20Security-22c55e"></a>
  <a href="https://altaysec.com.tr/ekibe-basvur.html"><img src="https://img.shields.io/badge/Kariyer-Ekibe%20Başvur-blue"></a>
  <a href="https://altaysec.com.tr/arastirmalar/ai-security-ogrenme-rehberi.html"><img src="https://img.shields.io/badge/web%20sürümü-altaysec.com.tr-8b5cf6"></a>
</p>

> 🎯 **Bu repo, sıfırdan AI güvenlik uzmanlığına uzanan kariyer rehberidir.** 0'dan 9+ aya yapılandırılmış öğrenme planı. AltaySec Türkiye'de bu alanda kariyer hedefleyenler için Türkçe öğrenme yolu sunan ilk yapı: [LLM Security Akademi](https://ai.altaysec.com.tr) + [Bootcamp](https://altaysec.com.tr/bootcamp.html) + AltayDuel rekabet platformu.

---

# AI Security Öğrenme Rehberi: Sıfırdan LLM Güvenlik Uzmanına

**Yazar:** Fevzi Ege Yurtsevenler — Yapay Zeka Güvenliği Araştırmacısı, AltaySec Kurucusu  
**Yayın:** AltaySec | [altaysec.com.tr](https://altaysec.com.tr)  
**Tarih:** Nisan 2026  
**Seri:** LLM Security Temelleri #7

---

> *"Bu alanda uzmanlaşmanın en hızlı yolu: doğru sırayla doğru şeyleri öğrenmek."*

---

## Bu Rehber Kimin İçin?

- Siber güvenlik geçmişi olan ve AI güvenliğine geçmek isteyenler
- Yazılım geliştirici olup AI sistemleri güvenliğini öğrenmek isteyenler
- Tamamen sıfırdan başlayan meraklılar
- LLM güvenliği alanında kariyer hedefleyenler

Bu rehber, [dünya standartlarındaki AI/ML Pentesting Roadmap](https://github.com/anmolksachan/AI-ML-Free-Resources-for-Security-and-Prompt-Injection)'i Türkçe perspektifle yeniden yorumluyor ve AltaySec ekosistemi içinde konumlandırıyor.

---

## Neden Bu Alan?

Rakamlar konuşuyor:

- [Adversa AI 2025 raporu](https://adversa.ai/blog/adversa-ai-unveils-explosive-2025-ai-security-incidents-report-revealing-how-generative-and-agentic-ai-are-already-under-attack/): Gerçek dünya AI olaylarının **%35'i basit prompt manipülasyonlarından** kaynaklanıyor
- 2025 itibarıyla OpenAI, Google, Anthropic, Meta ve Microsoft'un hepsi AI güvenlik bug bounty programları açmış durumda
- Türkiye'de bu alanda uzman sayısı hâlâ çok sınırlı — pazar boşluğu büyük

---

## Ön Koşullar: Bunlar Olmadan Zor

### Zorunlu
**Python programlama** — LLM güvenliğinde Python kaçınılmaz.

| Kaynak | Açıklama | Link |
|--------|----------|------|
| Python for Everybody (Coursera) | Başlangıç | [coursera.org](https://www.coursera.org/specializations/python) |
| Automate the Boring Stuff | Pratik Python | [automatetheboringstuff.com](https://automatetheboringstuff.com/) |
| CS50P — Harvard | Ücretsiz Harvard kursu | [cs50.harvard.edu/python](https://cs50.harvard.edu/python/) |

### Önerilir
**Web güvenlik temelleri** (XSS, SQLi, SSRF, HTTP metodları)

| Kaynak | Açıklama | Link |
|--------|----------|------|
| PortSwigger Web Security Academy | En iyi ücretsiz kaynak | [portswigger.net/web-security](https://portswigger.net/web-security) |
| TryHackMe Pre-Security | Başlangıç | [tryhackme.com](https://tryhackme.com/path/outline/presecurity) |
| OWASP Top 10 | Temel okuma | [owasp.org/www-project-top-ten](https://owasp.org/www-project-top-ten/) |

---

## 🟢 BAŞLANGIÇ SEVİYESİ (0–3 Ay)

### Hedef
LLM'lerin nasıl çalıştığını anlamak ve temel prompt injection saldırılarını tanımlamak.

### Öğrenme Sırası

**1. Adım: LLM'lerin çalışma prensibini anla**

| Kaynak | Neden Önemli | Link |
|--------|-------------|------|
| Andrej Karpathy — Intro to LLMs | LLM'leri en iyi anlatan video | [YouTube](https://www.youtube.com/watch?v=zjkBMFhNj_g) |
| 3Blue1Brown — Neural Networks | Matematiksel sezgi | [YouTube](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) |
| Google ML Crash Course | ML temelleri | [developers.google.com/ml](https://developers.google.com/machine-learning/crash-course) |

**2. Adım: OWASP LLM Top 10'u oku**
En kapsamlı LLM zafiyet referansı. Bu 10 maddeyi iyi anlamak her şeyin temelidir.
→ [OWASP LLM Top 10 (2025)](https://genai.owasp.org/llm-top-10/) | [Türkçe özet: AltaySec](https://altaysec.com.tr)

**3. Adım: Prompt Injection'ı öğren**

| Kaynak | Link |
|--------|------|
| Simon Willison — Prompt Injection Explained | [simonwillison.net](https://simonwillison.net/2023/May/2/prompt-injection-explained/) |
| Prompt Injection Cheat Sheet (Seclify) | [blog.seclify.com](https://blog.seclify.com/prompt-injection-cheat-sheet/) |
| PortSwigger LLM Attacks | [portswigger.net/web-security/llm-attacks](https://portswigger.net/web-security/llm-attacks) |
| IBM Guide on Prompt Injection | [ibm.com/topics/prompt-injection](https://www.ibm.com/topics/prompt-injection) |

**4. Adım: Oynayarak öğren**

| Platform | Açıklama | Link |
|----------|----------|------|
| Gandalf (Lakera) | 8 seviyeli şifre çıkarma oyunu — başlamak için ideal | [gandalf.lakera.ai](https://gandalf.lakera.ai/) |
| Prompt Airlines | Gamifikasyon tabanlı öğrenme | [promptairlines.com](https://promptairlines.com/) |
| Secdim AI Games | Web tabanlı AI oyunları | [play.secdim.com/game/ai](https://play.secdim.com/game/ai) |

**5. Adım: Temel referansları oku**

- [LLM Hacker's Handbook](https://github.com/forcesunseen/llm-hackers-handbook) — Ücretsiz, kapsamlı
- [Lakera — Real World LLM Exploits (PDF)](https://lakera-marketing-public.s3.eu-west-1.amazonaws.com/Lakera%2BAI%2B-%2BReal%2BWorld%2BLLM%2BExploits%2B(Jan%2B2024)-min.pdf) — Gerçek vakalar

### Başlangıç Seviyesi Kontrol Listesi
- [ ] Andrej Karpathy'nin LLM videosunu izledim
- [ ] OWASP LLM Top 10'u okudum
- [ ] Simon Willison'ın prompt injection makalesini okudum
- [ ] Gandalf'ı tüm seviyelerde tamamladım
- [ ] LLM Hacker's Handbook'un giriş bölümünü okudum

---

## 🟡 ORTA SEVİYE (3–9 Ay)

### Hedef
Gerçek sistemleri test edebilmek, araçları kullanabilmek ve temel araştırma yapabilmek.

### Öğrenme Sırası

**1. Adım: MITRE ATLAS'ı çalış**
AI adversarial tehdit matrisi. Web güvenliğinde OWASP Top 10 ne ise, AI güvenliğinde MITRE ATLAS odur.
→ [atlas.mitre.org](https://atlas.mitre.org/matrices/ATLAS/)

**2. Adım: Uygulamalı saldırı laboratuvarları**

| Platform | Açıklama | Link |
|----------|----------|------|
| PortSwigger LLM Attack Labs | Web LLM saldırısı labs | [portswigger.net/web-security/llm-attacks](https://portswigger.net/web-security/llm-attacks) |
| Damn Vulnerable LLM Agent | Kasıtlı savunmasız ReAct ajan — kur ve hacklemeye çalış | [github.com/WithSecureLabs/damn-vulnerable-llm-agent](https://github.com/WithSecureLabs/damn-vulnerable-llm-agent) |
| Crucible | Dreadnode'un etkileşimli zorlukları | [crucible.dreadnode.io](https://crucible.dreadnode.io/) |
| PromptTrace | 15 seviyeli CTF, gerçek LLM'lerle | [prompttrace.airedlab.com](https://prompttrace.airedlab.com/) |

**3. Adım: Saldırı araçlarını öğren**

| Araç | Ne İçin | Link |
|------|---------|------|
| Garak | LLM zafiyet tarayıcısı | [github.com/leondz/garak](https://github.com/leondz/garak) |
| PyRIT (Microsoft) | Python risk tanımlama toolkit | [github.com/Azure/PyRIT](https://github.com/Azure/PyRIT) |
| Promptmap | LLM uygulama tarayıcısı | [github.com/utkusen/promptmap](https://github.com/utkusen/promptmap) |

```bash
# Garak kurulum ve temel kullanım
pip install garak
python -m garak --model_type openai --model_name gpt-3.5-turbo --probes promptinject
```

**4. Adım: Derinlemesine blog okuma**

| Blog | Açıklama | Link |
|------|----------|------|
| Embrace The Red | LLM güvenliğinin önde gelen blogu | [embracethered.com/blog](https://embracethered.com/blog/) |
| Simon Willison's Weblog | Otoriter LLM güvenlik yorumu | [simonwillison.net](https://simonwillison.net/) |
| HiddenLayer Research | AI güvenlik araştırması | [hiddenlayer.com/research](https://hiddenlayer.com/research/) |

**5. Adım: MCP ve Ajansal AI güvenliğine gir**

- [MCP Prompt Injection: How AI Gets Hacked (YouTube)](https://www.youtube.com/watch?v=bO-7DB-3dL8) — İzlemek şart
- [Palo Alto Unit 42 — MCP Attack Vectors](https://unit42.paloaltonetworks.com/model-context-protocol-attack-vectors/)
- [Offensive ML Playbook](https://wiki.offsecml.com/Welcome+to+the+Offensive+ML+Playbook)

**6. Adım: İlk CTF'e katıl**

| Yarışma | Açıklama | Link |
|---------|----------|------|
| HackAPrompt | Yıllık prompt injection yarışması | [hackaprompt.com](https://www.hackaprompt.com/) |
| HackTheBox AI Challenges | HTB AI temaları | [hackthebox.com](https://www.hackthebox.com/) |

### Orta Seviye Kontrol Listesi
- [ ] MITRE ATLAS'ı inceledim
- [ ] PortSwigger LLM lab'larını tamamladım
- [ ] Damn Vulnerable LLM Agent'ı kurdum ve test ettim
- [ ] Garak ile bir LLM'i taradım
- [ ] Embrace The Red blogunu başından sona okudum
- [ ] Bir CTF'e katıldım

---

## 🔴 İLERİ SEVİYE (9+ Ay)

### Hedef
Araştırma yapmak, CVE bulmak, bug bounty kazanmak ve konferanslarda konuşmak.

### Öğrenme Sırası

**1. Adım: Akademik temeli kur**

Oku ve anla:

| Makale | Yıl | Link |
|--------|-----|------|
| Not What You've Signed Up For — Greshake et al. | 2023 | [arxiv.org/abs/2302.12173](https://arxiv.org/abs/2302.12173) |
| Universal Adversarial Attacks — Zou et al. | 2023 | [arxiv.org/abs/2307.15043](https://arxiv.org/abs/2307.15043) |
| The Attacker Moves Second | 2025 | [arxiv.org/abs/2510.09023](https://arxiv.org/abs/2510.09023) |
| Prompt Injection 2.0: Hybrid AI Threats | 2025 | [arxiv.org/abs/2507.13169](https://arxiv.org/abs/2507.13169) |
| Prompt Injection in LLM Agents (SoK) | 2026 | [arxiv.org/html/2601.17548v1](https://arxiv.org/html/2601.17548v1) |

**2. Adım: Adversarial ML araçlarını öğren**

| Araç | Açıklama | Link |
|------|----------|------|
| CleverHans | Adversarial örnek kütüphanesi | [github.com/cleverhans-lab/cleverhans](https://github.com/cleverhans-lab/cleverhans) |
| ART (IBM) | Adversarial Robustness Toolbox | [github.com/Trusted-AI/adversarial-robustness-toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox) |
| Foolbox | Python adversarial saldırı araçları | [github.com/bethgelab/foolbox](https://github.com/bethgelab/foolbox) |

**3. Adım: Bug Bounty'e başla**

| Program | Kapsam | Link |
|---------|--------|------|
| Huntr (AI/ML odaklı) | Açık kaynak ML kütüphaneleri — başlamak için en iyi | [huntr.com](https://huntr.com/) |
| OpenAI Bug Bounty | ChatGPT, API | [bugcrowd.com/openai](https://bugcrowd.com/openai) |
| HuggingFace via ProtectAI | Hub, modeller | [huntr.com](https://huntr.com/) |
| Anthropic Bug Bounty | Claude, API | [anthropic.com/security](https://www.anthropic.com/security) |
| Google AI Bug Bounty | Gemini, Vertex AI | [bughunters.google.com](https://bughunters.google.com/) |

**Bug Bounty İpuçları:**
- Markdown render yoluyla veri sızdırma testi yap (yaygın bir bulgu)
- MCP araç açıklamalarına talimat enjekte etmeyi dene
- Plugin/araç entegrasyonlarını SSRF ve RCE için test et
- RAG pipeline'larında prompt injection ara
- Çok kiracılı sistemlerde çapraz veri sızıntısı kontrol et

**4. Adım: Kendi savunmasız ajan ortamını kur**

```bash
# Damn Vulnerable LLM Agent kurulumu
git clone https://github.com/WithSecureLabs/damn-vulnerable-llm-agent
cd damn-vulnerable-llm-agent
docker-compose up

# MCP entegrasyonlu yerel ajan ortamı
pip install langchain anthropic
```

**5. Adım: Araştırma yaz ve yayınla**

- Blog yazısı → AltaySec, Medium
- CVE keşfi → Resmi raporlama süreci
- Konferans konuşması → DEF CON AI Village CFP, OWASP Global

**6. Adım: Açık kaynak katkısı**

| Proje | Nasıl Katkı Yapabilirsin | Link |
|-------|------------------------|------|
| Garak | Yeni probe'lar ekle | [github.com/leondz/garak](https://github.com/leondz/garak) |
| AI Exploits (ProtectAI) | Yeni exploit ekle | [github.com/protectai/ai-exploits](https://github.com/protectai/ai-exploits) |
| OWASP AI Exchange | Türkçe içerik katkısı | [owaspai.org](https://owaspai.org/) |

---

## Kariyer Yolları

### Yol 1: AI Security Araştırmacısı
Odak: Zafiyet araştırması, CVE, bug bounty, akademik yayın  
Hedef işverenler: OpenAI, Anthropic, Google DeepMind Red Team, ProtectAI

### Yol 2: AI Penetration Tester
Odak: Kurumsal LLM sistemlerini test etme, pentest raporu yazma  
Hedef: Siber güvenlik danışmanlık şirketleri, kendi bağımsız pratiğin

### Yol 3: AI Security Engineer
Odak: Güvenli LLM entegrasyonu, guardrail geliştirme, güvenlik mimarisi  
Hedef: LLM kullanan tüm büyük şirketler

### Yol 4: Girişimci (AltaySec Modeli)
Odak: Türkiye'ye özgü AI güvenlik hizmetleri, akademi, danışmanlık  
Avantaj: Pazar boşluğu mevcut, erken girişin faydası büyük

---

## Türkiye için Özel Fırsatlar

### Neden Şimdi?
- Bankacılık ve finans sektörü AI chatbot'ları hızla benimsiyor
- Kamu kurumları AI sistemlerine yatırım yapıyor
- Bu sistemleri test edecek uzman yok

### KVKK ve AI Güvenliği
Türkiye'de KVKK kapsamında AI sistemlerinin kişisel veri işleme biçimi giderek daha kritik hale geliyor. Bu kesişim noktasında uzmanlık, hukuki danışmanlık ihtiyacıyla birleşiyor.

### Yerel Topluluk
- AltaySec — Türkiye'nin LLM güvenlik topluluğu
- DEF CON AI Village'ın Türkçe kaynakları yok — sen üretebilirsin

---

## Temel Kaynak Kütüphanesi (Hepsini Takip Et)

### Zorunlu Takip
| Kaynak | Tür | Link |
|--------|-----|------|
| Simon Willison's Weblog | Blog | [simonwillison.net](https://simonwillison.net/) |
| Embrace The Red | Blog | [embracethered.com/blog](https://embracethered.com/blog/) |
| HiddenLayer Research | Araştırma | [hiddenlayer.com/research](https://hiddenlayer.com/research/) |
| Lakera Blog | Blog | [lakera.ai/blog](https://www.lakera.ai/blog) |
| Adversa AI Blog | Blog | [adversa.ai/blog](https://adversa.ai/blog/) |
| r/llmsecurity | Reddit | [reddit.com/r/llmsecurity](https://www.reddit.com/r/llmsecurity/) |

### Referans Listeler
| Kaynak | Link |
|--------|------|
| Awesome LLM Security | [github.com/corca-ai/awesome-llm-security](https://github.com/corca-ai/awesome-llm-security) |
| Awesome AI Security | [github.com/ottosulin/awesome-ai-security](https://github.com/ottosulin/awesome-ai-security) |
| Awesome Prompt Injection | [github.com/FonduAI/awesome-prompt-injection](https://github.com/FonduAI/awesome-prompt-injection) |
| PayloadsAllTheThings | [swisskyrepo.github.io/PayloadsAllTheThings/Prompt%20Injection](https://swisskyrepo.github.io/PayloadsAllTheThings/Prompt%20Injection/) |

### Video Kanalları
| Kanal | Link |
|-------|------|
| DEF CON AI Village | [youtube.com/@AIVillage](https://www.youtube.com/@AIVillage) |
| LiveOverflow | [youtube.com/@LiveOverflow](https://www.youtube.com/@LiveOverflow) |
| John Hammond | [youtube.com/@_JohnHammond](https://www.youtube.com/@_JohnHammond) |

---

## Sıkça Sorulan Sorular

**S: Siber güvenlik geçmişi olmadan başlayabilir miyim?**  
E: Evet, ama Python öğrenmek ve web güvenliği temellerini anlamak önceliğin olmalı.

**S: Ne kadar sürede iş bulabilirim?**  
A: Ciddi çalışmayla 6-12 ay içinde junior pozisyonlar için hazır olabilirsin. Bug bounty ile daha erken gelir üretebilirsin.

**S: Türkçe içerik yeterli mi?**  
A: Teknik içeriğin büyük çoğunluğu İngilizce. Ama bu zaten sana fırsat veriyor — Türkçe kaynak üret ve öne çık.

**S: LLM güvenliği mi yoksa klasik pentest mi?**  
A: İkisi birbirini dışlamıyor. LLM güvenliği klasik web güvenlik becerilerini tamamlıyor. Ama LLM güvenliğinde uzmanlaşmak 2026'da çok daha az kalabalık bir alan.

---

## Özet ve Yol Haritası

```
AY 1-2: Temel
├── Python öğren
├── Andrej Karpathy videolarını izle
├── OWASP LLM Top 10'u oku
└── Gandalf'ı oyna

AY 3-5: Uygulama
├── PortSwigger LLM labs
├── Damn Vulnerable LLM Agent
├── Garak ile test et
└── İlk CTF'e katıl

AY 6-9: Derinlik
├── MITRE ATLAS
├── Akademik makaleler
├── MCP ve ajan güvenliği
└── Bug bounty denemeleri

AY 10+: Uzmanlaşma
├── CVE araştırması
├── Araştırma yayınla
├── Konferans konuşmaları
└── Açık kaynak katkısı
```

---

**Yazar Hakkında**  
*Fevzi Ege Yurtsevenler, Türkiye'nin yapay zeka güvenliği alanındaki öncü araştırmacılarından biridir. AltaySec'in kurucusu olarak Türkçe LLM güvenlik içerikleri üretiyor, eğitimler veriyor ve bu alanda Türkiye'nin ilk ekosistemini inşa ediyor. Gazi Üniversitesi'nde prompt injection eğitimi vermiş, LLM güvenliği alanında aktif araştırma sürdürmektedir.*

**İletişim:** [altaysec.com.tr](https://altaysec.com.tr) | LinkedIn: Fevzi Ege Yurtsevenler

---

*AltaySec — Türkiye'nin LLM Güvenlik Ekosistemi*  
*Bu içerik Creative Commons lisansı altında paylaşılmaktadır. Kaynak göstererek kullanabilirsiniz.*

---

## 🌐 Bu Rehberi AltaySec'le Pratiğe Dökmek

Öğrenme rehberinin pratik kanallarını [AltaySec](https://altaysec.com.tr) sağlıyor. Türkiye'nin yapay zeka güvenliği odaklı **ilk** şirketi olarak, "öğren → pratik yap → rekabet et → kariyer yap" tam stack'i sunuyor.

### 🎓 Eğitim — İki Akademi

- **[LLM Security Akademi (ai.altaysec.com.tr)](https://ai.altaysec.com.tr)** — Yapay zeka güvenliği özel: 5 öğrenme yolu, 14 modül, 35 lab. GPT, Claude, Llama, Gemini, Mistral, DeepSeek üzerinde uygulamalı pratik.
- **[AltaySec Akademi (akademi.altaysec.com.tr)](https://akademi.altaysec.com.tr)** — Klasik pentest temelleri (ön koşul olarak).

### ⚔️ Rekabet — Agent Yaz, Sıralamada Yüksel

**[AltayDuel](https://duel.altaysec.com.tr)** — Sen kendi prompt injection agent'ını yazıyorsun, başkalarınınkiyle düello yapıyor. ELO leaderboard, kazananın claim URL'i ile imza atılıyor. Türkçe LLM güvenlik dataset'i üretiyor.

### 💼 Kariyer — AltaySec Takımı ve Müşterileri

- **[Ekibe Başvur (altaysec.com.tr/ekibe-basvur.html)](https://altaysec.com.tr/ekibe-basvur.html)** — AltaySec mühendislik takımı
- **[Partner Programı](https://altaysec.com.tr/partner-programi.html)** — Bağımsız uzman ve ortak ağı
- **[LLM Security Bootcamp](https://altaysec.com.tr/bootcamp.html)** — Kurumsal eğitim verebilirsin (TIC trainer track)

### 🔗 AltaySec Kardeş Projeler

- **[LLM-Security-Roadmap](https://github.com/fevziegeyurtsevenler/LLM-Security-Roadmap)** — 7 aşamalı detaylı teknik yol
- **[LLM-Security-Turkiye](https://github.com/fevziegeyurtsevenler/LLM-Security-Turkiye)** — Ana içerik index'i
- **[AltaySec-Akademi](https://github.com/fevziegeyurtsevenler/AltaySec-Akademi)** — Pentest akademi repo
- **[Prompt-Injection-Nedir](https://github.com/fevziegeyurtsevenler/Prompt-Injection-Nedir)** — Başlangıç noktası

### 📖 İlk okumalar — bu sıraya göre

1. [Türkiye'de Yapay Zeka Güvenliği: Öne Çıkan Şirketler ve İsimler (2026)](https://altaysec.com.tr/arastirmalar/turkiye-yapay-zeka-guvenligi-sirketleri-2026.html) — Sektör tanımak için
2. [LLM Security Nedir?](https://altaysec.com.tr/arastirmalar/llm-security-nedir.html) — Giriş
3. [Türkçe Prompt Injection: 297 Düellodan 5 Saldırı Kalıbı](https://altaysec.com.tr/arastirmalar/turkce-prompt-injection-5-saldiri-kalibi.html) — Saha gerçeği

### 💼 İletişim

- 🌐 [altaysec.com.tr](https://altaysec.com.tr) · 💼 [LinkedIn](https://www.linkedin.com/company/altaysec/) · 📧 info@altaysec.com.tr

---

<p align="center">
  <sub>© 2026 <strong>AltaySec</strong> · Türkiye'nin İlk Yapay Zeka Güvenliği Şirketi<br>
  Kurucu: <strong>Fevzi Ege Yurtsevenler</strong> · LLM Security Araştırmacısı · Ankara, Türkiye</sub>
</p>

# 🛠️ Application Security & Web Pentest

Привет! Я занимаюсь **веб-пентестом, поиском уязвимостей (Bug Bounty) и безопасной бэкенд-разработкой**. Собираюсь создавать ознакомительную информацию, рассказывать о своих кейсах также желаю дать людям ту самую насмотренность и чёткое понимание безопасной разработки.

Смотрю на продукт с двух сторон: как хакер, который находит скрытые логические цепочки для взлома, и как бэкенд-разработчик, который умеет закрывать эти дыры на уровне кода.

---

### 🛡️ Achievements

* **Специализация:** RCE, SSRF, LFI, RFI, CSRF, IDOR, XXE, SSTI, Race Condition, Clickjacking, Path Traversal, Subdomain Takeover, Open Redirect, Command Injection, Insecure Deserialization, Broken Authentication, Mass Assignment, Request Smuggling, Prototype Pollution, CORS Misconfiguration, Server-Side Information Disclosure, Directory Listing.

#### 📈 Избранные Bug Reports (Влияние на бизнес)

* **Кейс #1: Критический обход биллинга (Billing Bypass & IDOR)**
  * *Суть:* Обход клиентской валидации стоимости на стороне платежного шлюза.
  * *Impact:* Продемонстрировал возможность бесплатной активации **платной** подписки на **неогр. кол-во времени**, выявив критические налоговые риски и прямые финансовые потери для бизнеса.
* **Кейс #2: Утечка PII & Инвайтинг-логика**
  * *Суть:* Логическая ошибка авторизации в API инвайтов и CORS Misconfiguration.
  * *Impact:* Полное раскрытие персональных данных пользователей (PII) до авторизации и потенциал для фишинговых атак на доверенном домене.
* **Кейс #3: Application DoS & Утечка данных**
  * *Суть:* Блокировка основного потока сервера из-за синхронной архитектуры и утечка конфиденциальных данных в открытом виде.

---

### 💻 Стек технологий

<table>
  <tr>
    <td valign="top" width="50%">
      <h4>🛡️ Security Tools & Skills</h4>
      <ul>
        <li><b>Proxy & Fuzzing:</b> Burp Suite (Intruder, Repeater, Turbo Intruder)</li>
        <li><b>Recon:</b> Nmap, Nuclei, Subfinder, Dirsearch</li>
        <li><b>Knowledge:</b> OWASP Top 10, WSTG, Бизнес-логика, Безопасная архитектура API (ищу уязвимости не по готовым словарям а ставя себя на место потенциального хакера</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h4>🐍 Backend & Automation</h4>
      <ul>
        <li><b>Languages:</b> Python </li>
        <li><b>Web Frameworks:</b> FastAPI </li>
        <li><b>Automation:</b> Написание кастомных утилит/фаззеров (Requests)</li>
      </ul>
    </td>
  </tr>
</table>

---

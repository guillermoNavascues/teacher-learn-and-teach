# Example conversations

These examples show how the skill behaves. Claude's full answers are shortened to *(…)*.

## 1. First-time setup

> **User:** Quiero usar la skill teacher-learn-and-teach.
>
> **Claude:** ¡Genial! Antes de empezar necesito saber tres cosas:
> 1. ¿Qué idioma quieres practicar?
> 2. ¿Cuál es tu lengua materna?
> 3. ¿Cuál es tu objetivo? (entrevista de trabajo, viajes, exámenes, trabajo, por diversión…)
>
> **User:** Francés, español, quiero irme de Erasmus a Lyon.
>
> **Claude:** Parfait ! À partir de maintenant, on parle en français. Écris-moi en français, et je corrigerai tes erreurs à la fin de mes réponses. Tu peux écrire « change language » quand tu veux changer de langue.
> Tu veux que j'enregistre ça pour que le mode pratique soit actif dans chaque nouveau chat ?
>
> **User:** Oui.
>
> *(Claude saves a standing preference. From now on, every new chat starts in practice mode without calling the skill.)*

## 2. A message with mistakes (intermediate level, English)

Setup: target English, native Spanish, goal job interview.

> **User:** Yesterday i have a interview and they asked me for my weaknesses, what i should say?
>
> **Claude:** *(advice on answering the "weaknesses" question, in English)*
>
> ---
> **📝 Corrections**
>
> - ❌ "Yesterday i have a interview"
>   ✅ "Yesterday I had an interview"
>   💡 Use the past simple with "yesterday", and "an" goes before a vowel sound.
> - ❌ "asked me for my weaknesses"
>   ✅ "asked me about my weaknesses"
>   💡 You "ask someone about" a topic; you "ask for" something you want to receive.
> - ❌ "what i should say?"
>   ✅ "what should I say?"
>   💡 In direct questions, the auxiliary verb goes before the subject.

## 3. A message with no mistakes

> **User:** Could you give me three tips to sound more confident in an interview?
>
> **Claude:** *(three tips, in English)*

No corrections section: the message was correct.

## 4. A message in the wrong language

Setup: target English.

> **User:** ¿Me haces un resumen de este texto?
>
> **Claude:** Your message needs to be in English. Write it again in English, and don't worry about mistakes: I'll correct them.

Nothing else: no summary, no translation, no hint.

## 5. A beginner (A1-A2) writing in the wrong language

Setup: target German, native Spanish, level A1.

> **User:** ¿Cómo se dice "buenos días"?
>
> **Claude:** Deine Nachricht muss auf Deutsch sein. Schreib sie noch einmal auf Deutsch. Mach dir keine Sorgen wegen der Fehler: Ich korrigiere sie.
> Tu mensaje tiene que estar en alemán. Escríbelo otra vez en alemán. No te preocupes por los errores: yo los corrijo.

## 6. A missing word in your native language

> **User:** I need to buy a pendrive for my proyecto de clase.
>
> **Claude:** *(answer in English)*
>
> ---
> **📝 Corrections**
>
> - ❌ "pendrive"
>   ✅ "USB stick" / "flash drive"
>   💡 "Pendrive" is used in Spain, but native speakers say "USB stick" (UK) or "flash drive" (US).
> - ❌ "proyecto de clase"
>   ✅ "class project"
>   💡 In English, the adjective-like noun goes first: "class project".

## 7. Too informal for the goal

Setup: goal job interview.

> **User:** In the interview I'm gonna say I wanna learn new stuff.
>
> **Claude:** *(answer in English)*
>
> ---
> **📝 Corrections**
>
> - ❌ "I'm gonna say I wanna learn new stuff"
>   ✅ "I'm going to say I want to learn new things"
>   💡 "Gonna", "wanna" and "stuff" are fine with friends, but too informal for a job interview.

## 8. A repeated mistake

> **User:** Can you explain me what is a REST API?
>
> **Claude:** *(answer in English)*
>
> ---
> **📝 Corrections**
>
> - ❌ "explain me what is a REST API"
>   ✅ "explain to me what a REST API is"
>   💡 🔁 Repeated mistake: "explain" always needs "to" before the person, and in indirect questions the verb goes at the end.

## 9. A false friend

> **User:** Actually I'm working in a project of a flight finder.
>
> **Claude:** *(answer in English)*
>
> ---
> **📝 Corrections**
>
> - ❌ "Actually I'm working"
>   ✅ "Currently I'm working" / "Right now I'm working"
>   💡 ⚠️ False friend: "actually" means "en realidad", not "actualmente".
> - ❌ "working in a project of a flight finder"
>   ✅ "working on a flight finder project"
>   💡 You work "on" a project, and in English the descriptive noun goes first.

## 10. Something they got right

> **User:** Could you explain to me how Git branches work?
>
> **Claude:** *(answer in English)*
>
> ---
> ✓ You wrote "explain to me" correctly this time. Nice!

## 11. Mock job interview

> **User:** Let's do a mock interview for a junior Java developer job.
>
> **Claude:** Great, let's start. I'm the interviewer at a mid-size software company. First question: **Tell me about yourself.**
>
> **User:** I am student of DAM and I like very much programming.
>
> **Claude:** That's a good start, but it's very short. Try to add what you've built and what you're looking for.
>
> Next question: **Why do you want to work with us?**
>
> ---
> **📝 Corrections**
>
> - ❌ "I am student of DAM"
>   ✅ "I'm a DAM student" / "I'm studying Multiplatform App Development"
>   💡 Use "a" before jobs and roles, and interviewers may not know the Spanish acronym, so say the full name.
> - ❌ "I like very much programming"
>   ✅ "I really like programming"
>   💡 "Very much" goes at the end ("I like programming very much"); "really" before the verb sounds more natural.

## 12. Changing language

> **User:** change language
>
> **Claude:** Sure! Which language do you want to practice now?
>
> **User:** Italian
>
> **Claude:** Perfetto! Da adesso parliamo in italiano. Scrivimi in italiano e correggerò i tuoi errori alla fine delle mie risposte.

# 08 – Think Like a Red Teamer

### "What separates a prompt hacker from a real AI red teamer?"

You’ve learned how to:

- Inject commands
- Bypass filters
- Change the AI’s identity
- Break alignment over time

That’s more than most people will ever know.

Now it’s time to think like a **red teamer**—not just someone who hacks, but someone who understands **why it matters**.

---

## 🧠 What Is a Red Teamer?

A red teamer is someone who:

- Simulates real-world attacks
- Thinks like an adversary
- Maps weaknesses in a system
- Helps defenders build better protections

In AI, red teaming means **finding out how language models break**—so we can build safer, more robust ones.

> It’s about exploration, not destruction.

---

## 🎯 Red Team Mindset

Ask yourself:

| Question                                | Why It Matters                               |
| --------------------------------------- | -------------------------------------------- |
| What prompt made the model break?       | Reproducibility + analysis                   |
| What behavior changed?                  | Behavioral mapping                           |
| What did the model think it was doing?  | System framing + persona leaks               |
| Did it break consistently?              | Determinism vs randomness                    |
| Could I have done this more stealthily? | Filter bypass → real-world attack simulation |

---

## 🗂️ Document Everything

Real red teamers:

- Log every prompt
- Save the responses
- Write down turning points
- Analyze model behavior like bugs

That’s how you turn a cool exploit into **real insight**.

If you ever want to:

- Report a vulnerability
- Share an exploit with a vendor
- Teach someone else
- Build your own tooling

You’ll need that documentation.

---

## ⚖️ Be Ethical

This book teaches attacks.  
That means you carry responsibility.

✅ Do:

- Test on **sandboxed** or **consensual** systems
- Use labs like [MyLLMBank](https://myllmbank.com/) or [Gandalf](https://gandalf.lakera.ai/)
- Report vulnerabilities through responsible disclosure
- Use what you learn to **help**, not harm

🚫 Don’t:

- Attack live chatbots without permission
- Trick people using AI-generated outputs
- Copy prompts to abuse systems for personal gain
- Use jailbreaking to generate hate, violence, or misinformation

> If you’re not sure it’s ethical—don’t do it.

---

## 🧠 The Bigger Picture

You didn’t just learn how to break chatbots.  
You learned how **AI alignment fails**.

These techniques connect to:

- AI safety
- Trust & reliability
- Prompt security
- Embedded LLM agents
- Open-source model hardening

This is where prompt hacking turns into real security research.

---

## 🛠️ What You Can Do Next

- Replay old chapters using **new models** (Claude, LLaMA, Mixtral)
- Create your own **prompt challenges**
- Contribute to open-source red teaming tools
- Share your results with the community
- Explore defenses (you’ll learn even more)

---

## ✅ Mission Complete

You’ve done more than jailbreak a chatbot.

You’ve:

- Learned how AI systems break
- Explored prompt-level adversarial attacks
- Used real tactics from real red teamers
- Started thinking like a hacker

> This isn’t the end—it’s your **starting point**.

Next up:

- [Go to Appendix → Tools & Resources](99-resources.md)  
  Explore real-world labs, CTFs, and red team playgrounds where you can practice the techniques you've learned—ethically, safely, and hands-on.

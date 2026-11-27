# Narration Sections

**Read order:** sequential, with one consistent narrator voice, microphone perspective, pace, and processing across all sections. Section headings are not spoken.

**Voice direction:** Mature, medium-deep neutral American voice; composed, investigative, natural emphasis; no imitation of a specific narrator. Short paragraph breaths only.

## 01. Cold Open: The Silent Printer — target 00:00–00:50

In a central bank in Dhaka, a printer was supposed to turn digital payment messages into paper records.

On the morning after a series of transfers, the tray was empty.

At first, that looked like a familiar office problem. Printers fail. Systems freeze. Work carries on.

But this time, the missing pages concealed something extraordinary: payment instructions sent in Bangladesh Bank’s name had moved tens of millions of dollars out of its account at the Federal Reserve Bank of New York.

The full attempt was far larger. Nearly one billion dollars was targeted.

Most of it did not leave.

About 81 million dollars did.

And by the time the bank understood what had happened, the money was already moving through the financial system—and into the casinos of the Philippines.

## 02. Chapter 1: A Message That Could Move Money — target 00:50–01:55

To understand the heist, separate two things that are often confused: a payment message and the money itself.

SWIFT—the Society for Worldwide Interbank Financial Telecommunication—is a secure messaging network used by banks and financial institutions. It carries standardized instructions. It does not hold customer funds or directly move money.

In this case, Bangladesh Bank held funds in an account at the Federal Reserve Bank of New York. A SWIFT message, if accepted and processed, could instruct the Fed to transfer money from that account to other banks.

The attackers did not need to break into the Federal Reserve’s vault. They needed to make fraudulent instructions appear to come from Bangladesh Bank.

Those instructions used the bank’s legitimate access to SWIFT. The attack targeted the bank’s own systems and controls around that access.

The distinction matters. SWIFT’s core messaging service was not reported to have been breached. The compromised point was the environment from which Bangladesh Bank’s messages were prepared and sent.

A trusted channel. A stolen identity. And instructions that looked authentic enough to enter the payment process.

## 03. Chapter 2: Access Before the Transfers — target 01:55–03:20

The attackers did not arrive on the night of the transfers and improvise. Investigators found signs that access had been established earlier.

A U.S. Justice Department complaint said the conspiracy gained access to Bangladesh Bank’s computer network after compromising it with spear-phishing emails. Spear-phishing is a targeted message designed to trick a recipient into opening a file, following a link, or otherwise giving an attacker a way in.

The exact path from initial access to control of the payment environment has not been fully established in public records. Reporting described malware and malicious tools on systems connected to the bank’s SWIFT operations. BAE Systems researchers later identified custom malware designed to interact with SWIFT Alliance Access software.

The tools could help the attackers disguise what was happening locally—interfering with records and making messages harder for bank staff to spot.

The attackers needed access and preparation. They had to learn how the bank processed payments, create instructions that would pass as legitimate, and reduce the chance that staff would see immediate evidence of them.

The malware was part of that plan. So was the printer.

## 04. Chapter 3: The Orders — target 03:20–04:35

On February 4, 2016, the attackers sent fraudulent payment instructions through Bangladesh Bank’s SWIFT environment.

The U.S. indictment later described 35 attempted transfers totaling about 951 million dollars. The orders directed funds from Bangladesh Bank’s account at the New York Fed to accounts in other countries.

The scale was striking. But the messages were not a single command to drain an account. They were separate payment instructions, each with a destination and an amount.

Some were rejected or held for review. Others raised questions. The attempted transactions were unusual in ways that included their size, the beneficiaries, and information in the payment messages.

The operation’s outcome came down to several points of friction across institutions and time zones.

Four transfers to the Philippines, totaling about 81 million dollars, went through.

A fifth transfer—about 20 million dollars intended for a nonprofit in Sri Lanka—was stopped after a routing bank sought clarification. The beneficiary name was misspelled: “fandation” instead of “foundation.”

That typo mattered. It helped prompt a question the attackers could not answer from inside Bangladesh Bank’s systems.

The largest loss was still enormous—but the attempted theft had been much larger.

## 05. Chapter 4: What the Printer Told Them — target 04:35–05:55

Bangladesh Bank’s SWIFT setup was configured to print records of payment messages. The paper trail helped staff see what had been sent and what confirmations had come back.

The printer’s failure did not, by itself, explain the heist. It helped keep the activity out of view.

According to the bank officials’ account reported at the time, staff noticed missing printouts and tried to recover them manually. The SWIFT-connected software also became unresponsive. The bank then attempted to contact the New York Fed and sent stop-payment messages as it recognized that unauthorized transfers might have occurred.

This is what the printer incident actually means. It was not a printer accidentally “saving” the bank. Nor was the printer the system that moved the money. It was a monitoring and visibility failure, reportedly caused or exploited as part of the attack, that delayed recognition and response.

A paper process had become a security control. But paper is a weak control when no one is alerted that the record is missing.

The heist exposed a gap between what the bank believed it had sent, what its systems recorded, and what counterparties were seeing.

By the time the alarm was raised, the money that had cleared was no longer sitting at the first destination.

## 06. Chapter 5: From New York to Manila — target 05:55–07:25

The 81 million dollars reached accounts at Rizal Commercial Banking Corporation in the Philippines. From there, the funds were rapidly moved and converted.

Investigators and journalists traced portions through remittance channels and into the Philippine casino industry. Some of the money was converted into Philippine pesos. Some was associated with casino junket operators—businesses that bring high-stakes gamblers to casinos and handle money connected to their play.

Casinos became a crucial part of the money trail because the funds could move quickly through a sector with different reporting rules and oversight at the time. Once money was converted, transferred, or mixed with other funds, it became harder to follow and recover.

This was not a simple transfer from one account to another. It was laundering: moving illicit funds through transactions and intermediaries to obscure their origin.

The money trail also revealed a second story. Digital theft depended on human institutions at every stage—banks, remittance firms, casino operators, investigators, and courts. Each handoff created a new opportunity to detect the fraud. Each delay gave the money more room to disappear.

Recovery was partial. Philippine authorities later returned approximately 15 million dollars to Bangladesh. That was significant, but it represented only a fraction of the 81 million dollars stolen.

The title says the money vanished. More precisely, most of it became difficult to trace and recover after it moved beyond the first bank accounts.

## 07. Chapter 6: The Investigation and Attribution — target 07:25–08:40

The investigation crossed borders because the crime did.

Bangladesh worked with foreign law enforcement and financial authorities to trace the transfers, examine affected systems, and pursue recovery. Forensic researchers analyzed malware associated with the operation. Their findings helped show that the attackers had tools tailored to the bank’s SWIFT environment.

In 2018, the U.S. Justice Department publicly charged North Korean programmer Park Jin Hyok in a criminal complaint. Prosecutors alleged that he was part of a North Korean government-backed conspiracy that included the Bangladesh Bank theft. In 2021, the Justice Department announced an indictment against three North Korean military hackers that also alleged involvement in the Bangladesh heist.

These are important official attributions. They are allegations in U.S. legal filings, not a public trial that resolved every question about who performed each action.

Attribution in cyber investigations is built from evidence: malware similarities, infrastructure, operational patterns, communications, and links to other activity. It is rarely a single smoking gun.

The public record does not answer every question. It does establish the broad mechanics: attackers gained unauthorized access to the bank’s network, abused the bank’s payment environment, sent fraudulent SWIFT messages, and attempted to hide the resulting activity.

The case was not simply a story of clever code. It was a story of code exploiting weaknesses in processes, oversight, and verification.

## 08. Chapter 7: Where the Defenses Failed — target 08:40–10:20

No single safeguard could have solved this alone. The failure was layered.

First, attackers reached a sensitive payment environment. That points to the need for strict isolation, controlled access, and monitoring of systems that can originate high-value instructions.

Second, the bank’s local records could not be trusted as the only source of truth. If a compromised system can alter or suppress its own evidence, records need to be independently captured and reconciled.

Third, the payment instructions should have triggered stronger scrutiny. Large, unusual transfers to unfamiliar beneficiaries deserve out-of-band confirmation—verification through a separate, trusted channel.

Fourth, the bank’s monitoring depended in part on paper printouts and staff noticing that they were missing. A resilient process should generate immediate alerts when confirmations fail, when messages do not match approved instructions, or when a payment departs sharply from normal patterns.

Finally, speed matters. Cross-border payment systems are designed to move legitimate transactions efficiently. That efficiency also gives fraud a narrow window in which to be detected and stopped.

After the heist, SWIFT introduced its Customer Security Programme, requiring users to meet a baseline of security controls and share information about their security environments. The larger lesson applies beyond SWIFT: a secure network cannot guarantee that every participant’s computers, credentials, and procedures are secure.

Trust is distributed. So must be the defenses.

## 09. Chapter 8: What Changed—and What Did Not — target 10:20–11:45

The heist changed how financial institutions talked about cyber risk. It made clear that a bank could be attacked through the systems it used to access an otherwise trusted payment network.

It also showed why basic controls matter most when the stakes are high: segmented networks, multi-person authorization, secure credentials, tamper-resistant logs, anomaly detection, and tested incident response.

These measures sound routine. Their value is that they work together.

If an attacker reaches one workstation, network controls can limit where they go. If credentials are stolen, transaction controls can demand another approval. If a payment is unusual, monitoring can flag it. If local records are manipulated, independent logs can expose the mismatch. If the first warning is missed, a rehearsed response can still contain the damage.

And the controls must be tested. A policy document cannot stop a payment. A printer cannot be the only alert system. A bank cannot assume that a message is legitimate because it came through a familiar channel.

The Bangladesh Bank heist did not prove that global finance is defenseless. It revealed how a chain of ordinary weaknesses can combine into a spectacular loss.

And it left an uncomfortable question for every institution connected to the financial system:

If your own systems were compromised tonight, would you know which instructions were real?

## 10. Closing: The Missing Record — target 11:45–12:45

The heist began with access. It succeeded because fraudulent instructions passed through trusted processes. And it became harder to stop when the records meant to reveal those instructions were missing.

The printer was a small detail in a much larger failure. But it captured the central problem: the bank’s view of its own activity had been compromised at the moment it needed that view most.

About 81 million dollars left Bangladesh Bank. Some was recovered. Most was not.

The attempted theft was close to a billion.

The lesson is not that one typo or one broken printer can decide the fate of global finance. It is that payment security depends on layers—technical, human, and institutional—and every layer must be able to question the one before it.

A message can look authentic.

A system can report that nothing happened.

And sometimes, the first evidence of a crime is the record that never prints.

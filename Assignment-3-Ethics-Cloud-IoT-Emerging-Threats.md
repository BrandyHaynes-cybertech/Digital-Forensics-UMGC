# Ethics, Cloud Forensics, IoT Evidence & Emerging Threats
**Course:** CCJS 321 — Digital Forensics in the Criminal Justice System  
**Institution:** University of Maryland Global Campus (UMGC)  
**Author:** Brandy Haynes  

---

## Question 1: Ethical Dilemmas in Digital Forensics

### Dilemma 1 — Privacy Rights vs. Evidence Collection

One common ethical dilemma a digital forensic practitioner may encounter involves a suspect's right to privacy, particularly when the practitioner is exposed to sensitive information outside the scope of a warrant.

The 2016 San Bernardino shooting is a landmark example. The FBI attempted to compel Apple to create a backdoor to bypass security measures and access the suspect's iPhone. Apple refused on Fourth Amendment and privacy grounds. A judge later ruled the government cannot compel manufacturers to break customer data confidentiality.

**Best Practices to Protect Integrity:**
- Always obtain a warrant or legal authorization before conducting any digital forensic analysis
- Document every step taken, even if it seems redundant or minor
- Limit access to gathered information and share only what is necessary on a need-to-know basis
- Store collected data securely to prevent unauthorized access
- Use gathered information solely for the purpose of the investigation — never for personal gain

### Dilemma 2 — Human Bias and Algorithmic Bias

A second ethical dilemma involves human bias and bias within the algorithms and tools used in digital forensics. As Martijn van Otterlo noted in a 2017 article, while people often associate computers and their algorithms with objectivity, this is not always the case. Both humans and technology can only act upon a situation based on experience or the point of view from which an application was created.

**Confirmation bias** is particularly dangerous in investigations. When forensic experts begin to see and collect evidence only through a lens that confirms their existing belief — rather than following where the facts lead — it can result in the wrongful exoneration or condemnation of an innocent party. Justice cannot be served when all angles of an investigation are not explored.

---

## Question 2: Cloud Storage as a Source of Digital Evidence

Cloud storage refers to a system that allows users to store, access, or share data and files remotely over a network, typically housed on servers in a data center. Cloud storage has become critically important to investigations as the majority of the population now uses it daily — particularly in education and healthcare.

### Challenges for Investigators

Traditional digital forensics involves seizing physical devices such as hard drives, laptops, or servers to physically lock down and preserve the chain of custody. Cloud storage makes this impossible — data is stored redundantly across multiple servers, and investigators cannot retrieve deleted files, logs, or use typical recovery methods as they would on a physical device.

Additional challenges include:
- **Jurisdiction** — who has legal authority over cloud infrastructure
- **Contradictory or absent laws** — no standardized best practices exist for cloud forensics tools
- **Fourth Amendment debates** — ongoing legal battles over privacy rights in the cloud

Investigators should always seek legal authorization when obtaining cloud data, though current law provides little precise guidance for every scenario.

---

## Question 3: IoT Devices as Sources of Digital Evidence

### Fitness Watches

Fitness watches function as both a traditional timepiece and a health tracking device. Depending on the model, a Fitbit can track steps, heart rate, oxygen levels, sleep duration, exercise logs, and nutritional data. Some models function similarly to a full smartwatch or cellular device.

**Forensic Value:** GPS location, timestamps, heart rate, activity levels, sleep and movement patterns. For example — a suspect claims to be asleep during the time a crime was committed, but fitness watch data reveals elevated activity levels during that exact window. Data is typically synced to a manufacturer's app and can be accessed by confiscating the paired device or via the cloud account through the service provider.

### IoT and Vehicles

Modern vehicles are equipped with infotainment and telematics systems, GPS navigation, built-in Wi-Fi, and remote access capabilities — placing them firmly within the Internet of Things. Services like OnStar can automatically notify emergency services after a collision.

**Forensic Value:** Location data, IP addresses, web history, connected device logs, speed data, emergency service call records, and key fob data including VIN, GPS coordinates, mileage, and fuel levels.

A 2017 Digital Forensics Magazine article described a hit-and-run with no witnesses. Investigators detained a suspect whose SUV's telematics system confirmed the vehicle had been driving with its lights off in the exact location and time of the incident. Certain manufacturers like Tesla also periodically upload telematics data to their own servers — creating another source of evidence including software update logs, charging times, and detailed driving habit records.

### Drones

Drones have grown from recreational use to tools leveraged in criminal and terrorist operations — including espionage, target surveillance, contraband smuggling, and direct attacks. They have also been used in rescue missions and disaster response.

**Forensic Value:** Video surveillance footage, aerial imagery, GPS coordinates, flight logs and routes. Drone metadata and controller ID can identify the owner. While drones typically use physical data cards, sophisticated models simultaneously upload data to a cloud application — meaning even if the physical device is destroyed, evidence may still be recoverable.

---

## Question 4: Emerging Technologies and Terrorism

### Generative AI

Generative AI uses machine learning to generate content from large data sets. While it has significant beneficial applications, it also presents major risks. Terrorist organizations could use AI to:

- Create convincing disinformation and propaganda that is difficult to distinguish from reality
- Deploy AI-powered chatbots for interactive recruitment — identifying potential recruits via bots before switching to human contact
- Train operatives in augmented reality environments

To combat these threats, counterterrorism units must upgrade their technologies, hire investigators skilled in machine learning and AI, and implement counter-propaganda and de-radicalization initiatives. Pattern analysis to predict attacks and identify recruitment targets will be critical — though these measures will inevitably create new legal and civil liberties debates around free speech and privacy.

### Biotechnology

Biotechnology advancements present another emerging threat vector. Chile documented at least 17 chemical, biological, radiological, or nuclear threats between 1990 and 2022. Potential misuse includes:

- Engineered pathogens or lab-created viruses weaponized to target populations
- Biological attacks on food supplies or crops
- Cognitive manipulation through advances in understanding human biology

Molecular biologist Matthew Meselson warned in 2020 that every major technology in history has been exploited for hostile purposes, and biotechnology's rapid advancement will enable new ways to manipulate or destroy human life.

**Countermeasures:** Rapid diagnostics, biosensors, surveillance technology, and AI-enhanced detection. CRISPR-based tools such as SHERLOCK (Specific High Sensitivity Enzymatic Reporter Unlocking) can detect minute traces of genetic material in the field — a critical first step in identifying and responding to a biotechnological attack.

---

## References

1. Barnhart, H. (n.d.). Finding digital evidence in wearable tech. Forensic Magazine. https://www.forensicmag.com/3425-Featured-Article-List/584355-Finding-Digital-Evidence-in-Wearable-Tech/
2. Case IQ. (n.d.). Digital evidence in the cloud: A challenge for investigators. https://www.caseiq.com/resources/digital-evidence-in-the-cloud-a-challenge-for-investigators/
3. First Responder's Toolbox | Joint Counter Terrorism Assessment Team. (n.d.). Emerging technologies may heighten terrorist threats. https://www.odni.gov/files/NCTC/documents/jcat/firstresponderstoolbox/134s_-_First_Responders_Toolbox_-_Emerging_Technologies_May_Heighten_Terrorist_Threats.pdf
4. InfoSec Train | Medium. (n.d.). What are the challenges of cloud forensics? https://medium.com/@Infosec-Train/what-are-the-challenges-of-cloud-forensics-f2b1d85187db
5. Jaju, A. (n.d.). Ethical digital forensics — Balancing investigation procedures with privacy concerns. Logology. https://www.lexology.com/library/detail.aspx?g=fb018971-9604-405b-a13c-2ec2e3c19fcc
6. Maratsi, M. I., et al. (n.d.). Ethical and legal aspects of digital forensics algorithms. ACM Digital Library. https://dl.acm.org/doi/fullHtml/10.1145/3560107.3560114
7. Nakade, S. I. (n.d.). Privacy concerns and ethical issues in digital forensics. IRJMETS. https://www.irjmets.com/uploadedfiles/paper/issue_6_june_2024/58622/final/fin_irjmets1717564480.pdf
8. National Center for Biotechnology Information. (n.d.). Biotechnology research in an age of terrorism. https://www.ncbi.nlm.nih.gov/books/NBK222045/
9. Nelu, C. (n.d.). Exploitation of generative AI by terrorist groups. ICCT. https://www.icct.nl/publication/exploitation-generative-ai-terrorist-groups
10. Police Executive Research Forum. (n.d.). Utilizing vehicle data in law enforcement investigations. https://www.iacpcybercenter.org/wp-content/uploads/2020/09/Vehicle-Data_LECC-Article.pdf
11. Susan Sim, Eric Hartunian, and Paul J. Milas, ed. Emerging technologies and terrorism: An American perspective. US Army War College. https://press.armywarcollege.edu/cgi/viewcontent.cgi?article=1963&context=monographs
12. Tesla. (n.d.). Model 3 owner's manual — Vehicle telematics. https://www.tesla.com/ownersmanual/model3/en_us/
13. Weinstein, S. (n.d.). Law enforcement's new ally: The rise of counter-drones. Sentrycs. https://sentrycs.com/the-counter-drone-blog/law-enforcements-new-ally-the-rise-of-counter-drones/

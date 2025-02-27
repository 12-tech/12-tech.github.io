# Welcome to My Portfolio  

<img src="https://github.com/12-tech/12-tech.github.io/blob/main/IMG_3459.jpg?raw=true" 
     alt="Your Name" 
     width="500" 
     loading="lazy">  

Solving complex problems with technology is my superpower. I thrive on dissecting challenges, diving deep into their intricacies, and crafting innovative solutions.  

As a hands-on **Embedded Systems Engineer**, I blend technical expertise with a relentless curiosity for learning, whether it’s mastering new tools or exploring cutting-edge methodologies.  

Don’t just take my word for it; explore my featured projects below to see how I turn ideas into impact.  

This portfolio reflects my journey in **embedded systems, machine learning, and collaborative problem-solving**. I’m always eager to connect with like-minded innovators.  
**Let’s build something meaningful together!**  

📩 **Contact me:** [adijatsulaimon01@gmail.com](mailto:adijatsulaimon01@gmail.com)  

---

## **🌍 Language Toggle**  

You can view this portfolio in **English** or **German**.  
Click the button below to switch languages!  

<button id="toggle-lang">Switch to German</button>  

---

## **🚀 Featured Projects**  

### **[Smart House: Simulation of Energy Supply and Consumption](https://github.com/Group-B-Java/Java_project.git)**  
<img src="https://yourcdn.com/smart-house.jpg" alt="Smart House Project" width="500" loading="lazy">  
A Smart House system that **manages energy supply and consumption** using Java for automation.  

---

### **[Cross-Traffic Management for Autonomous Vehicles](https://github.com/12-tech/Cross-Traffic-management-for-autonomous-vehicles.git)**  
<img src="https://yourcdn.com/traffic-management.jpg" alt="Traffic Management" width="500" loading="lazy">  
An autonomous vehicle traffic management system for **intersection safety and efficiency**, built with **C++, VHDL, and FreeRTOS**, utilizing object detection and tracking algorithms.  

---

### **[Labeling of Sugarbeet Plants Using Active Learning (Bachelor Thesis)](https://github.com/12-tech/Labeling-using-Active-Learning.git)**  
<img src="https://yourcdn.com/labeling.jpg" alt="Labeling with Active Learning" width="500" loading="lazy">  
A **machine learning algorithm** that employs **active learning** and deep learning techniques to efficiently annotate sugarbeet plants, **reducing manual labeling efforts** and improving model performance using Python.  

---

## **📞 Contact**  

📧 **Email**: [adijatsulaimon01@gmail.com](mailto:adijatsulaimon01@gmail.com)  
🔗 **LinkedIn**: [linkedin.com/in/adijat01/](https://www.linkedin.com/in/adijat01/)  
💻 **GitHub**: [github.com/12-tech](https://github.com/12-tech)  

**Thank you for visiting!** 🚀 I’m always open to discussing exciting new projects, collaborations, or just connecting to share knowledge.  

---

## **🌍 Language Toggle (JavaScript for GitHub Pages)**  

If you're hosting this on **GitHub Pages**, add this **JavaScript** to enable the language toggle feature:  

```html
<script>
const translations = {
    en: {
        projects: "Featured Projects",
        smart_house: "A Smart House system that manages energy supply and consumption using Java for automation.",
        traffic_management: "An autonomous vehicle traffic management system for intersection safety and efficiency.",
        labeling: "A machine learning algorithm that employs active learning and deep learning techniques."
    },
    de: {
        projects: "Hervorgehobene Projekte",
        smart_house: "Ein Smart-Home-System, das die Energieversorgung und den Verbrauch mit Java automatisiert.",
        traffic_management: "Ein Verkehrsmanagementsystem für autonome Fahrzeuge zur Erhöhung der Sicherheit und Effizienz.",
        labeling: "Ein maschinelles Lernverfahren, das Active Learning verwendet, um Pflanzen effizient zu annotieren."
    }
};

document.getElementById("toggle-lang").addEventListener("click", function () {
    const lang = document.body.getAttribute("lang") === "en" ? "de" : "en";
    document.body.setAttribute("lang", lang);
    document.getElementById("projects-title").innerText = translations[lang].projects;
    document.getElementById("smart-house-desc").innerText = translations[lang].smart_house;
    document.getElementById("traffic-management-desc").innerText = translations[lang].traffic_management;
    document.getElementById("labeling-desc").innerText = translations[lang].labeling;
    this.innerText = lang === "en" ? "Switch to German" : "Switch to English";
});
</script>

# GoodBoy.AI

Final project for the Building AI course  
Building AI course project

## Summary

GoodBoy.AI is an AI-powered health and diet planner for dogs. It helps dog owners make data-based feeding and wellness decisions by analysing breed, age, activity, and symptoms, turning random online guesses into vet-friendly, personalised plans.


## Background

Many dog owners struggle to balance affection with proper care. They rely on random online advice, social-media tips, or generic vet charts that rarely fit their pet’s unique needs. As a result, dogs are over, or under-fed, supplements are misused, and small health issues go unnoticed until they escalate.

* problem 1 – Pet health information online is fragmented, inconsistent, and often unverified  
* problem 2 – Owners find it hard to track diet, weight, activity, and symptoms in one place  
* problem 3 – Personalized nutritional guidance is expensive and not easily available in developing countries  

My motivation: I’m a lifelong dog owner who knows how stressful it is to decode what’s “right” for your dog’s diet or exercise. I wanted a simple AI that helps people understand their dog’s needs instead of guessing or feeling guilty. This project matters because better data-based care means healthier, happier dogs and less emotional and financial strain on their humans.


## How is it used?

GoodBoy.AI is designed for everyday dog owners, not just professionals. The user opens a simple dashboard or mobile app and enters key details: dog’s breed, age, weight, daily activity, and any visible symptoms or behaviour changes.  

The AI then analyses this data to:  
* Suggest balanced meal portions and feeding times  
* Recommend safe treat limits based on calories and activity  
* Flag possible warning signs for vet attention  
* Offer preventive care reminders like vaccinations, flea treatments, or check-ups  

Example use case:  
An owner notices their dog has been scratching more lately. They log this symptom, and GoodBoy.AI suggests possible causes (allergies, flea reaction, dry skin), recommends a temporary diet tweak, and advises when to visit a vet.  

The solution can be used anytime, from daily feeding checks to long-term health tracking, and becomes a personal “dog health companion” that learns and adjusts as the dog grows.


## Data sources and AI methods

GoodBoy.AI combines verified veterinary datasets with user-generated inputs.  
Data sources could include:  
* Public vet nutrition databases (breed standards, calorie needs, weight charts)  
* Open-access datasets from animal health research organisations  
* Crowdsourced data from users (weight logs, symptoms, diet outcomes)  

The AI component would use lightweight models suited for structured, low-risk recommendations:  
* **Classification** - to map symptoms and behaviours to possible health categories (e.g. skin, digestion, dental)  
* **Recommendation systems** - to generate meal plans and treat suggestions using nutritional rules  
* **Simple predictive analysis** - to forecast ideal weight trends or detect sudden changes  
* **Natural language processing** - to let owners describe symptoms in plain English and still get relevant insights  

The system focuses on assisting, not replacing, professional veterinary care. It converts scattered information into personalized, practical guidance — the way a digital “dog nutritionist” would.

## Challenges

GoodBoy.AI cannot and should not replace professional veterinary care. It can guide owners to make smarter daily choices, but diagnosis and treatment always require a vet.

* The accuracy of suggestions depends on the quality of data entered by the user: incomplete or incorrect inputs can lead to wrong recommendations.  
* Breed-specific datasets may not include enough information for mixed breeds or rescue dogs.  
* Predictive insights (like weight or allergy trends) rely on consistent logging; without that, the system can only offer generic tips.  
* Ethical consideration: user data privacy must be protected, especially health information about pets, which can include location and owner details.  
* In regions with limited access to reliable internet or vet networks, AI advice could be misused as a replacement for real diagnostics.  

The goal is to support responsible ownership, not automate pet healthcare.

## What next?

GoodBoy.AI can grow into a full ecosystem for pet wellness.  
Next steps could include:  
* Integrating **IoT collars or smart feeders** to collect live activity and meal data  
* Partnering with local vets and clinics for verified nutritional feedback  
* Adding a **chat-based symptom checker** to improve real-time guidance  
* Training the model with **regional diet data** to make it relevant globally  
* Offering an API for pet-care apps and insurance providers  

To move forward, the project would need access to real veterinary datasets, UX design for pet owners, and basic model training resources. With enough data and collaboration, GoodBoy.AI could become the everyday health assistant every dog parent wishes existed.

## Acknowledgments

* Inspired by my own experiences as a dog owner and the need for accessible, data-based pet care.  
* References and datasets: open veterinary nutrition guidelines and public research by the World Small Animal Veterinary Association (WSAVA).  
* Markdown and README structure based on the Building AI course template by Minnalearn and the University of Helsinki.  
* Concept inspired by the growing trend of AI-assisted health monitoring tools for humans and pets alike.


# **App\_Flow\_Pages\_Roles.md – AI Learning Blueprint Platform**

## **📌 User Roles**

* **Single role (MVP):** All users are equal — no admin panel in MVP  
* (Future: role-based access for moderators, admins)

---

## **📋 App Pages & Functions**

### **1\. Landing Page**

* Introduction to platform: headline, CTA to get started  
* Overview of how it works (3-step visual or text)  
* Login / Sign up buttons

### **2\. Sign-Up / Login Pages**

* Email \+ password fields  
* Optional OAuth (future)  
* Link to privacy, terms

### **3\. Onboarding Survey (Post Signup)**

* Goal (dropdown or text input)  
* Coding experience (radio buttons)  
* Time commitment (radio)  
* Learning style (radio)  
* Save answers to user profile

### **4\. Dashboard (Post Onboarding)**

* Overview of blueprints (grid or list)  
* “Create new blueprint” button  
* Option to switch between blueprints

### **5\. Create Blueprint Page**

* Form with AI prompt input  
* Option to reuse onboarding info  
* Submit to trigger OpenAI call  
* Loading animation during generation

### **6\. Blueprint Detail Page**

* Title, description, steps/week-by-week layout  
* Resource links under each step  
* Save progress per step (checkboxes or toggles)  
* Edit title, duplicate plan, delete option  
* Upgrade callout for limited users

### **7\. Saved Resources Library**

* List of bookmarked items  
* Filter by type, tag, source  
* Add to blueprint from here

### **8\. Resource Discovery Page**

* Search bar, filters (type, topic, source)  
* Cards or list view  
* Button to save or copy into a blueprint

### **9\. Pricing & Upgrade Page**

* Compare Free vs Pro features  
* Stripe checkout button  
* Confirmation of plan and billing cycle

### **10\. Settings / Profile Page**

* View/update onboarding info  
* Subscription status (Free/Pro)  
* Link to manage Stripe subscription  
* Password change / logout

### **11\. Error & Empty States**

* Blueprint: “No plans yet” → CTA to create  
* Resources: “Nothing saved yet” → CTA to explore  
* Loading / Fail: “Something went wrong – try again”

---

## **🧭 User Flow Summary**

1. Land on homepage → Sign up  
2. Fill onboarding survey → Dashboard  
3. Click “Create blueprint” → Enter goal → Generate  
4. View and track blueprint → Save resources  
5. Explore library → Bookmark resources  
6. Hit feature limit → Visit Pricing → Upgrade via Stripe  
7. Access saved resources and blueprint archive from dashboard


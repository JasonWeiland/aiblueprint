# **Implementation\_Plan.md – AI Learning Blueprint Platform**

## **Phase 1: Lean MVP (Weeks 1–6)**

### **Week 1 – Project Setup**

* Initialize project in Lovable and connect to GitHub repo  
* Set up Supabase project and configure schema (Users, Blueprints, Resources)  
* Configure Vercel deployment and environment variables (OpenAI, Supabase)

### **Week 2 – User Authentication & Onboarding**

* Set up Supabase Auth (email/password)  
* Create onboarding survey (goals, time, coding experience)  
* Store responses in user profile

### **Week 3 – OpenAI Blueprint Generation**

* Integrate OpenAI via Supabase function  
* Design AI prompt templates based on survey inputs  
* Generate and save personalized blueprints in Supabase

### **Week 4 – Frontend Blueprint UI**

* Build create/view blueprint UI in Lovable  
* Display steps, resources, and progress indicators  
* Implement loading states and AI result formatting

### **Week 5 – Resource Bookmarking & Stripe Setup**

* Create SavedResources table and bookmark functionality  
* Add Stripe integration for paid subscriptions  
* Set free vs Pro plan limits (e.g. max blueprints)

### **Week 6 – QA and Launch Prep**

* Test all user flows (signup → generate → upgrade)  
* Deploy to production via Vercel  
* Review OpenAI usage and error handling

---

## **Phase 2: Full Launch (Weeks 7–12+)**

### **Week 7–8 – Enhanced Blueprint Experience**

* Add progress tracking (steps completed)  
* Allow blueprint renaming and duplication  
* Enable regenerate step feature

### **Week 9–10 – Resource Library**

* Build searchable Resource Library  
* Allow resource tagging, filters, and detail view  
* Add “Save to Library” from anywhere

### **Week 11–12 – Subscriptions & Exports**

* Google Drive export integration (blueprint → Google Doc)  
* Email onboarding and monthly updates via Resend/Postmark  
* Stripe customer portal integration for subscription management

---

## **Phase 3: Expansion (Post-MVP)**

* YouTube API integration for real-time video search  
* Public blueprints (sharable read-only URLs)  
* Social features (explore, comment, like, remix blueprints)  
* Community leaderboard or challenge boards  
* AI-assisted idea validation and roadmap generation


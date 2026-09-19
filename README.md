# Indian Diet Fitness Tracker 🥗

A personalized fitness tracker specifically designed for people following an Indian diet. FitDhaba accurately calculates calories and macronutrients from traditional Indian foods, then provides smart recommendations based on your health conditions, fitness goals, and personal parameters.

## 🎯 Problem Statement

Most fitness trackers have a Western-centric food database with inaccurate portions and nutritional values for Indian cuisine. People in India struggle to:
- Find accurate calorie counts for home-cooked Indian meals
- Track macros for regional dishes (dal, curries, rotis, rice dishes)
- Get diet recommendations that account for their specific health conditions
- Find portion sizes in Indian units (bowl, roti, cup) instead of grams

**how we solves this** by building an Indian-first fitness tracker that understands Indian food, Indian health conditions, and Indian dietary habits.

## 🌟 Core Features

### 1. **Food Logging**
   - Log Indian foods by name (e.g., "Chole bhature", "Sambar", "Biryani")
   - Support for both vegetarian and non-vegetarian Indian cuisine
   - Portion sizes in Indian units: 1 bowl, 2 rotis, 1 cup, handful, etc.
   - Accurate calorie and macro calculation (protein, carbs, fats)
   - Track micronutrients important for Indian diets: iron, calcium, vitamin B12

### 2. **Personalized Daily Targets**
   - Input basic health info: age, gender, weight, height, activity level
   - Set fitness goals: weight loss, muscle gain, athletic performance, general health
   - App calculates daily calorie target and macro ratios automatically
   - Adjusts targets based on your health conditions

### 3. **Health Condition Customization**
   Personalized macro recommendations for:
   - **Diabetes**: Lower carb ratios, focus on fiber
   - **PCOS**: Higher protein, lower refined carbs
   - **Thyroid issues**: Selenium, iodine tracking
   - **High Blood Pressure**: Sodium monitoring
   - **Kidney Disease**: Potassium and protein limits
   - **Celiac/Gluten Sensitivity**: Filter gluten-free Indian foods
   - **Anemia**: Iron-rich food suggestions

### 4. **Smart Recommendations**
   - Real-time feedback on what you're eating
   - "Your lunch is protein-heavy, add some vegetables"
   - "Iron intake is low - try spinach or fortified roti"
   - "You have 200 calories left for snack - here are 3 options"
   - Suggest healthier Indian alternatives (bajra roti vs refined flour, etc.)

### 5. **Time-Aware Macro Targets**
   - Different macro needs for breakfast, lunch, dinner, snacks
   - Morning meals might be higher carb, evening meals higher protein
   - Adjusts recommendations based on meal timing

### 6. **Progress Tracking**
   - Daily calorie and macro consumption vs targets
   - Weekly/monthly progress charts
   - Track weight changes over time
   - Nutrient intake patterns
   - Visual progress dashboard

### 7. **Meal Planning**
   - Get suggested meal plans for the week
   - Plans based on your goals and health conditions
   - Variety of regional Indian cuisines
   - Can set dietary preferences (vegetarian, vegan, specific region, etc.)

### 8. **Smart Grocery Lists**
   - Auto-generate shopping lists from meal plans
   - Shows quantities needed
   - Helps plan groceries for the week
   - Cost estimation for budgeting

### 9. **Indian Food Education**
   - Learn health benefits of Indian spices: turmeric, cumin, fenugreek, etc.
   - Traditional food combinations and their nutritional benefits
   - Seasonal eating tips based on Ayurveda principles
   - Regional cuisine information

## 💡 How It Works

### **Step 1: User Setup**
User provides:
- Age, gender, weight, height
- Activity level (sedentary, light, moderate, very active, athlete)
- Fitness goal (weight loss, muscle gain, athletic performance, general health)
- Timeline (how many months to reach goal)
- Health conditions (if any)
- Dietary preferences (vegetarian, vegan, regional preference)

**App calculates**: Daily calorie target, ideal macro ratios, specific micronutrient needs

### **Step 2: Daily Food Logging**
User logs food by typing or voice:
- "2 rotis aloo gobi sabzi"
- "1 bowl moong dal"
- "1 cup rice with fish curry"

**App looks up**: Portion sizes, calories, all macronutrients, and micronutrients

### **Step 3: Real-Time Feedback**
As user logs food throughout the day:
- Shows remaining calories/macros
- Alerts if macros are imbalanced
- Suggests what to eat next based on what's left in the day
- Tracks hydration, fiber, key micronutrients

### **Step 4: Smart Recommendations**
Based on health condition and goals:
- "You're 45g short on protein today - add paneer or dal to dinner"
- "Calcium intake is low - drink buttermilk or add sesame seeds"
- "Great job on fiber today! Your digestive health is on track"
- "For weight loss, aim for lighter options in evening"

### **Step 5: Weekly Insights**
- Progress toward fitness goal
- Which foods helped most
- Nutritional patterns
- Suggestions for next week

## 🎯 Supported Health Conditions

- Type 1 & Type 2 Diabetes
- PCOS (Polycystic Ovary Syndrome)
- Thyroid disorders (Hypo & Hyperthyroid)
- Hypertension (High Blood Pressure)
- Kidney disease
- Celiac disease / Gluten sensitivity
- IBS (Irritable Bowel Syndrome)
- Anemia
- Heart disease
- General wellness

## 🏋️ Fitness Goals

- **Weight Loss**: Caloric deficit, high protein
- **Muscle Gain**: Caloric surplus, high protein, strength-focused macros
- **Athletic Performance**: Performance-optimized macros
- **General Health**: Balanced nutrition, wellness focus
- **Manage Health Condition**: Focus on managing specific condition through diet

## 👥 Target Users

- **Indians living in India**: Tracking traditional home-cooked meals
- **Diaspora**: Indians abroad wanting to track Indian food
- **Health-conscious people**: Managing weight or health conditions with Indian diet
- **Athletes**: Optimizing performance with Indian nutrition
- **People with medical conditions**: Diabetes, PCOS, thyroid issues who need Indian food guidance

## 📊 Example: What a User Sees

```
TODAY'S PROGRESS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Target: 1800 cal | Consumed: 1550 | Remaining: 250 cal

MACRONUTRIENTS
Protein:  65g / 135g (48%) ████░░░░░░ ADD PROTEIN
Carbs:    185g / 200g (92%) █████████░ ON TRACK
Fat:      42g / 50g (84%) ████████░ ON TRACK

MICRONUTRIENTS
Iron:     12mg / 21mg ██████░░░░ GOOD
Calcium:  400mg / 1000mg ████░░░░░░ NEEDS WORK
B12:      1.2mcg / 2.4mcg ██░░░░░░░░ NEEDS WORK

💡 SUGGESTIONS FOR REMAINING 250 CAL
• 200ml Buttermilk (Chaach) - 100 cal, adds calcium & B12
• Sprouts chaat with 1 tbsp peanut chutney - 150 cal, adds protein
• 1 cup Moong dal soup - 120 cal, adds protein & fiber
• 1 bowl Curd rice with cucumber - 140 cal

📈 THIS WEEK
✓ Protein intake improved
⚠ Calcium low - add more dairy or fortified foods
✓ Weight down 0.5kg from last week
```

## Future scope

- Photo-based food recognition (take a pic of your plate)
- Barcode scanning for packaged foods
- Integration with fitness trackers (steps, exercise data)
- Recipe suggestions based on available ingredients
- Community recipe sharing
- Regional language support (Hindi, Tamil, Telugu, Kannada)
- Mobile app (iOS/Android)
- Voice logging
- AI nutritionist chatbot



---


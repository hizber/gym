# 🏋️‍♂️ Complete Gym Program System Recreation Prompt

## 📋 System Overview
This prompt will generate a complete 4-day hypertrophy-focused gym program system with interactive exercise guides, Jefit integration, and professional formatting.

## 🎯 Recreation Prompt

```
Create a complete 4-day hypertrophy-focused gym program system with the following specifications:

## MAIN PROGRAM FILE: Hypertrophy_Program_English.md

### Structure Requirements:
1. **Header**: "💪 4-Day Hypertrophy-Focused Training Program"
2. **Table of Contents** with anchor links to all sections including:
   - Program Overview
   - Weekly Schedule  
   - Day 1: Chest + Shoulders
   - Day 2: Back + Biceps
   - Day 3: Legs + Glutes
   - Day 4: Arms + Core
   - Progression Strategy
   - Nutrition Guidelines
   - Important Notes
   - Tracking System
   - Expected Results
   - Exercise Demonstrations and Technical Tips
   - Additional Resources
   - Complete Exercise Guide Library

3. **Weekly Schedule Table**:
   - Monday: Chest + Shoulders (35-40 min)
   - Tuesday: Back + Biceps (35-40 min) 
   - Thursday: Legs + Glutes (40 min)
   - Saturday: Arms + Core (30-35 min)

4. **Daily Workouts** - Each day should include:
   - 5-7 exercises per day
   - 4 sets x 12 reps format
   - Exercise names as clickable links: `[Exercise Name](./exercises/Exercise_Name_Guide.md)`
   - Brief technique tips for each exercise
   - Appropriate emojis for visual appeal

5. **Exercise List to Include**:
   **Day 1 (Chest + Shoulders):**
   - Barbell Bench Press
   - Incline Dumbbell Press  
   - Dumbbell Flyes
   - Military Press
   - Lateral Raises
   - Rear Delt Flyes

   **Day 2 (Back + Biceps):**
   - Pull-ups/Lat Pull-down
   - Barbell Rows
   - Seated Cable Rows
   - T-Bar Rows
   - Barbell Bicep Curls
   - Hammer Curls

   **Day 3 (Legs + Glutes):**
   - Barbell Back Squat
   - Romanian Deadlift
   - Bulgarian Split Squats
   - Leg Press
   - Walking Lunges
   - Calf Raises

   **Day 4 (Arms + Core):**
   - Close-Grip Bench Press
   - Dumbbell Bicep Curls
   - Tricep Dips
   - Cable Bicep Curls
   - Overhead Tricep Extension
   - Planks
   - Russian Twists

6. **Complete Exercise Guide Library Section** listing all exercises with checkmarks and descriptions

## EXERCISE GUIDES FOLDER: exercises/

Create individual comprehensive guides for each exercise with this exact format:

### File Naming Convention:
- Use underscores: `Exercise_Name_Guide.md`
- Examples: `Barbell_Bench_Press_Guide.md`, `Lateral_Raises_Guide.md`

### Guide Content Structure:
```markdown
# 💪 [Exercise Name] - Complete Training Guide

## 🎯 Exercise Variations & Demonstrations

### 1. [Primary Variation Name]
![Exercise GIF](https://www.jefit.com/images/exercises/[exercise-id].gif)

**Equipment:** [Equipment type]
**Difficulty:** [Beginner/Intermediate/Advanced] 
**Type:** [Compound/Isolation]
**Primary muscles:** [Muscle groups]

#### Step-by-Step Technique:
1. [Detailed step 1]
2. [Detailed step 2] 
3. [Detailed step 3]
4. [Continue with all steps]

**🔗 Jefit Reference:** [Exercise Name](https://www.jefit.com/exercises/[exercise-id])

### 2. [Secondary Variation Name]
[Repeat same format for each variation]

## 📋 Programming Guidelines
[Programming information]

## ⚠️ Safety Notes
[Safety considerations]

## 🎯 Performance Standards
[Beginner/Intermediate/Advanced standards]

## 🔄 Exercise Alternatives
[Alternative exercises]

---
**[← Back to Main Program](../Hypertrophy_Program_English.md)**
```

### Jefit Integration Requirements:
1. **Use fetch_webpage tool** to extract exercise information from jefit.com
2. **Search for exercises** using terms like "jefit [exercise name]" 
3. **Extract from each Jefit page**:
   - Exercise title
   - Animated GIF URL
   - Equipment requirements  
   - Difficulty level
   - Exercise type (compound/isolation)
   - Primary muscle groups
   - Step-by-step instructions
4. **Include direct Jefit links** for each exercise variation

### Formatting Standards:
- Use consistent emoji headers (💪 🎯 📋 ⚠️ 🔄)
- Include back-navigation links to main program
- Professional markdown formatting
- Clear section separations with horizontal rules
- Bullet points for instructions
- Bold formatting for key terms

### File Structure:
```
gym/
├── Hypertrophy_Program_English.md (main program)
└── exercises/
    ├── Barbell_Bench_Press_Guide.md
    ├── Incline_Dumbbell_Press_Guide.md  
    ├── Dumbbell_Flyes_Guide.md
    ├── Military_Press_Guide.md
    ├── Lateral_Raises_Guide.md
    ├── Rear_Delt_Flyes_Guide.md
    ├── Pull_ups_Lat_Pull_down_Guide.md
    ├── Barbell_Rows_Guide.md
    ├── Seated_Cable_Rows_Guide.md
    ├── T_Bar_Rows_Guide.md
    ├── Barbell_Bicep_Curls_Guide.md
    ├── Hammer_Curls_Guide.md
    ├── Barbell_Back_Squat_Guide.md
    ├── Romanian_Deadlift_Guide.md
    ├── Bulgarian_Split_Squats_Guide.md
    ├── Leg_Press_Guide.md
    ├── Walking_Lunges_Guide.md
    ├── Calf_Raises_Guide.md
    ├── Close_Grip_Bench_Press_Guide.md
    ├── Dumbbell_Bicep_Curls_Guide.md
    ├── Tricep_Dips_Guide.md
    ├── Cable_Bicep_Curls_Guide.md
    ├── Overhead_Tricep_Extension_Guide.md
    ├── Planks_Guide.md
    └── Russian_Twists_Guide.md
```

## EXECUTION STEPS:
1. Create main program file with complete structure and navigation
2. Create exercises folder
3. For each exercise guide:
   - Search Jefit for exercise variations (minimum 2-3 per guide)
   - Extract GIFs, equipment, difficulty, instructions
   - Create comprehensive guide with consistent formatting
   - Include multiple variations where applicable
4. Link all exercises in main program to respective guides
5. Ensure all relative links work properly (./exercises/Exercise_Guide.md)

## QUALITY REQUIREMENTS:
- All exercises must have working Jefit GIF integrations
- Consistent professional formatting throughout
- Complete navigation system with working links
- Comprehensive exercise variations (2-5 per guide)
- Detailed step-by-step instructions for each variation
- Safety notes and programming guidelines
- Performance standards for progression tracking

Create this complete system with full Jefit integration, professional formatting, and comprehensive exercise coverage.
```

## 📚 Usage Instructions

1. **Copy the prompt above** (everything within the code block)
2. **Paste into AI assistant** (Claude, ChatGPT, etc.)
3. **Ensure the assistant has access to**:
   - File creation tools
   - Web scraping/fetch capabilities  
   - String replacement tools
4. **The system will automatically**:
   - Create the main program file
   - Generate all exercise guides with Jefit integration
   - Set up proper file linking and navigation
   - Apply consistent formatting throughout

## 🎯 Expected Output

- **1 Main Program File**: Complete 4-day workout program with table of contents and linked exercises
- **25+ Exercise Guide Files**: Individual comprehensive guides with Jefit GIFs and detailed instructions
- **Professional Formatting**: Consistent markdown styling with emojis and proper structure
- **Full Navigation System**: Working relative links between all files
- **Jefit Integration**: Embedded exercise GIFs and reference links throughout

## 📝 Customization Options

You can modify the prompt to:
- **Change program focus** (strength, endurance, etc.)
- **Adjust workout split** (3-day, 5-day, etc.)  
- **Modify exercise selection** (add/remove specific exercises)
- **Update formatting style** (different emojis, structure)
- **Change exercise database** (replace Jefit with other sources)

---

**💡 Tip:** This prompt creates a complete, professional gym program system that can be used across different platforms and devices with full markdown compatibility.

---

*Created: November 2025 | Complete Gym Program System Recreation Template*
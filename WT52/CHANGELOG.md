# 🧍‍♂️ WT52 Feedback Update Summary

**Major Update Highlights**
- **All** in-game parts now last **2.5× longer** (10h → 25h).
- **Fully balanced Advanced Food** at minimum all food will be 50 subtotal unless it is intermediate.
- **Butcher Elk and Campfire Elk** new recipes available to provide this hunt more use.
- **Butcher byproduct balanced** scrap meat, fur pelt, leather hide, shorn wool have all been adjusted for balancing - this fixes market excess and shortages.
- **Skin tiny animals** available to hunters to help offset early game animal byproducts.
- **Carcass weight generally reduced** across the board.
- **Wiring reassigned** to Blacksmiths to have more utility (Copper Wiring & Gold Wiring).
- **Streamlined profession requirements** for ethanol, cheese, yeast, and biodiesel.
- **Incinerate Garbage** now scales and levels up self-improvement slightly
---

# 🧍‍♂️ All Players

**Durability & Maintenance**
- All in-game parts had `ReduceMaxDurabilityByPercent` adjusted **0.05 → 0.02**
  → Part lifespan increased from **~10 hours → ~25 hours** across all professions and crafting tiers.
  - Affected Parts:
    - **Carpenter Profession:**
      - **Logging:** Wooden Oar
      - **Paper Milling:** Paper
      - **Shipwright:** Hemp Mooring Rope, Metal Rudder, Small Wooden Ship Frame, Wooden Hull Planks
    - **Engineer Profession:**
      - **Basic Engineering:** Iron Wheel, Wooden Gear, Wooden Wheel
      - **Electronics:** Advanced Circuit, Basic Circuit, Electric Motor, Fuse
      - **Industry:** Advanced Combustion Engine, Rubber Wheel, Steel Gear, Steel Gearbox, Steel Plate
      - **Mechanics:** Boiler, Combustion Engine, Copper Plate, Gearbox, Iron Gear, Iron Plate, Piston, Portable Steam Engine, Servo
    - **Hunting Profession:**
      - **Butchery:** Lubricant
    - **Mason Profession:**
      - **Glassworking:** Fiberglass, Light Bulb
      - **Masonry:** MillStone, Mortar
    - **Scientist Profession:**
      - **Oil Drilling:** Plastic
    - **Smith Profession:**
      - **Blacksmith:** Cooking Utensils, Copper Wiring, Iron Saw Blade, Steel Saw Blade
    - **Tailor Profession:**
      - **Tailoring:** Cotton Fabric, Linen Fabric

**Crafting Tables**
- All power consuming crafting tables now consume **0 durability per hour of use** (`DurabilityUsedPerHourOfUse`) to prevent duplicate durability drain on parts. This caused all crafting tables like a Mill to last for 10 hours instead of our expected duration. Which is now **only** based on crafting an item uses the new `0.02` per craft. **5 ReduceMaxDurabilityByPercent -> 0 ReduceMaxDurabilityByPercent**:  
  - **Affected Professions:**
    - **Carpenter Profession:**
      - **Carpentry:** Sawmill
      - **Composites:** AdvancedCarpentryTable
    - **Chef Profession:**
      - **Advanced Cooking:** Stove
    - **Engineer Profession:**
      - **Electronics:** ElectronicsAssembly
      - **Industry:** ElectricLathe, ElectricMachinistTable, ElectricPlaner, ElectricStampingPress, RoboticAssemblyLine
      - **Mechanics:** AssemblyLine, Lathe, ScrewPress, Shaper StampMill
    - **Farming Profession:**
      - **Milling:** Mill
    - **Mason Profession:**
      - **Advanced Masonry:** AdvancedMasonryTable
      - **Mining:** Arrastra, FrothFloatationCell, JawCrusher, ScreeningMachine, SensorBasedBeltSorter
    - **Scientist Profession:**
      - **Oil Drilling:** InjectionMoldMachine, PumpJack
    - **Smith Profession:**
      - **Advanced Smelting:** RollingMill
      - **Blacksmith:** PowerHammer
    - **Tailor Profession:**
      - **Tailoring:** AdvancedTailoringTable, AutomaticLoom, SpinMelter
---

# 🥐 Advanced Baking

- **Bearclaw**
  - Carbs **14 → 17**
  - Protein **4 → 6**
  - Fat **21 → 22**
  - Subtotal **46 → 52**
  - Calories **850 → 900**

- **FruitTart**
  - Fat **9 → 11**
  - Subtotal **48 → 50**

- **HeartyHometownPizza**
  - Protein **7 → 12**
  - Subtotal **49 → 54**

- **Pirozhok**
  - Vitamins **4 → 7**
  - Subtotal **47 → 50**
  - Calories **850 → 1000**

- **StuffedTurkey**
  - Carbs **17 → 12**
  - Vitamins **7 → 12**

- **TastyTropicalPizza**
  - Vitamins **11 → 15**
  - Subtotal **50 → 54**

---

# 🍲 Advanced Cooking

- **AgoutiEnchiladas**
  - Fat **27 → 23**
  - Subtotal **58 → 54**
  - Calories **800 → 950**

- **BanhXeo**
  - Carbs **26 → 20**
  - Protein **17 → 23**
  - Fat **10 → 11**
  - Subtotal **57 → 58**

- **BearSUPREME**
  - Protein **22 → 23**
  - Subtotal **60 → 61**

- **BoiledRice**
  - Ingredient: `Sugar` **0 → 2**
  - Ingredient: `Oil` **0 → 2**

- **CornFritters**
  - Vitamins **8 → 12**
  - Subtotal **47 → 51**

- **CrimsonSalad**
  - Protein **7 → 6**
  - Subtotal **56 → 55**

- **ElkTaco**
  - Fat **22 → 14**
  - Vitamins **6 → 18**
  - Subtotal **51 → 55**
  - Calories **1050 → 850**

- **FriedHareHaunches**
  - Carbs **6 → 12**
  - Vitamins **4 → 0**
  - Subtotal **52 → 54**
  - Calories **750 → 1250**

- **Hosomaki**
  - Output **2 → 1**
  - Calories **700 → 850**

- **KelpyCrabRoll**
  - Output **2 → 1**
  - Calories **1050 → 850**
  - Carbs **22 → 10**
  - Vitamins **5 → 17**

- **MillionairesSalad**
  - Carbs **18 → 14**
  - Protein **6 → 10**
  - Fat **6 → 5**
  - Vitamins **26 → 27**

- **PineappleFriedRice**
  - Calories **800 → 1200**
  - Carbs **20 → 25**
  - Protein **9 → 13**
  - Fat **12 → 13**
  - Vitamins **12 → 4**
  - Subtotal **53 → 55**
  - Ingredient: `BoiledRiceItem` **4 → 3**

- **PokeBowl**
  - Output **2 → 1**
  - Calories **1100 → 1000**
  - Carbs **21 → 14**
  - Protein **10 → 18**
  - Fat **11 → 5**
  - Vitamins **7 → 16**
  - Subtotal **49 → 53**

- **SearedMeat**
  - Carbs **4 → 0**
  - Protein **19 → 26**
  - Fat **17 → 26**
  - Vitamins **7 → 0**
  - Subtotal **47 → 52**

- **SeededCamasRoll**
  - Output **2 → 1**
  - Ingredient: `CamasPasteItem` **8 → 2**
  - Ingredient: `FiddleheadsItem` **8 → 2**
  - Calories **1050 → 850**

- **SpikyRoll**
  - Output **2 → 1**
  - Calories **1300 → 850**
  - Carbs **20 → 14**
  - Protein **17 → 18**
  - Fat **7 → 10**
  - Vitamins **2 → 9**
  - Subtotal **46 → 51**

- **WildMix**
  - Carbs **15 → 18**
  - Vitamins **21 → 22**
  - Subtotal **46 → 50**

---

# 🐾 Hunter

**Animals**
- **Snapping Turtle:**
  - Health **4.5 → 2.5**
- **Turkey:**
  - Health **2 → 1.5**

**Carcass Weight Adjustments**
- **AgoutiCarcass:** Weight **2000 → 500**
- **BisonCarcass:** Weight **5500 → 6000**
- **CoyoteCarcass:** Weight **2000 → 1500**
- **FoxCarcass:** Weight **2000 → 1500**
- **HareCarcass:** Weight **1000 → 500**
- **OtterCarcass:** Weight **1000 → 500**
- **PrairieDogCarcass:** Weight **1000 → 500**
- **SnappingTurtleCarcass:** Weight **2000 → 500**
- **TurkeyCarcass:** Weight **1000 → 500**
- **WolfCarcass:** Weight **2000 → 1500**

---

**New: Skinning Recipes**
- **SkinHare**
  - Profession: *None → Hunting*
  - Ingredient: `HareCarcass` **0 → 1**
  - Output: `FurPelt` **0 → 1**
  - Output: `ShornWool` **0 → 1**
  - ExperienceOnCraft: **0 → 2**
  - Calories in Labor: **0 → 25** *(With Bonus of Hunting)*
  - Crafting Time: **0 → 30 Seconds** *(With Bonus from ButcheryFocused / ButcheryParallel)*
  - Crafting Table: `FletchingTable`

- **SkinTinyAnimal**
  - Profession: *None → Hunting*
  - Ingredient: `TinyLeatherCarcass` **0 → 1**
  - Output: `LeatherHide` **0 → 1**
  - ExperienceOnCraft: **0 → 2**
  - Calories in Labor: **0 → 25** *(With Bonus of Hunting)*
  - Crafting Time: **0 → 30 Seconds** *(With Bonus from ButcheryFocused / ButcheryParallel)*
  - Crafting Table: `FletchingTable`

- **SkinTinyFurAnimal**
  - Profession: *None → Hunting*
  - Ingredient: `TinyFurCarcass` **0 → 1**
  - Output: `FurPelt` **0 → 1**
  - ExperienceOnCraft: **0 → 2**
  - Calories in Labor: **0 → 25** *(With Bonus of Hunting)*
  - Crafting Time: **0 → 30 Seconds** *(With Bonus from ButcheryFocused / ButcheryParallel)*
  - Crafting Table: `FletchingTable`

---

# 🍖 Campfire Cooking / Butchery

**New: Elk Recipes**
- **Campfire Elk**
  - Profession: *None → CampfireCooking*
  - Ingredient: `ElkCarcass` *(Added)*
  - Output: `CharredMeat` **0 → 7**
  - Output: `TallowItem` **0 → 2**
  - ExperienceOnCraft: **0 → 5**
  - Calories in Labor: **0 → 25** *(With Bonus of CampfireCooking)*
  - Crafting Time: **0 → 4 Minutes** *(With Bonus from CampfireCookingFocused / CampfireCookingParallel)*
  - Crafting Table: `Campfire`

- **Butcher Elk**
  - Profession: *None → Butchery*
  - Ingredient: `ElkCarcass` **0 → 1**
  - Output: `RawMeat` **0 → 7**
  - Output: `LeatherHide` **0 → 3**
  - Output: `FurPelt` **0 → 1**
  - ExperienceOnCraft: **0 → 5**
  - Calories in Labor: **0 → 70** *(With Bonus of Butchery)*
  - Crafting Time: **0 → 2 Minutes** *(With Bonus from ButcheryFocused / ButcheryParallel)*
  - Crafting Table: `ButcheryTable`

**Rebalance Butchery Byproducts**
- **ButcherMediumAnimal**
  - Output: `LeatherHide` **1 → 3**

- **ButcherMediumWoolyAnimal**
  - Output: `ShornWool` **2 → 4**

- **ButcherBison**
  - Ingredient: `ShornWool` **3 → 1**

**Butchery Recipes**
- **PreparedMeat**
  - Output: `ScrapMeat` **4 → 2**
- **PrimeCut**
  - Ingredient: `RawMeat` **16 → 12**
  - Output: `ScrapMeat` **0 → 3**
- **RawBacon**
  - Output: `ScrapMeat` **3 → 2**
---

# ⚙️ Blacksmith / Mechanics / Glassworking

**Profession Reassignments**
- **CopperWiring**
  - Profession: *Mechanics → Blacksmith*
  - Ingredient Bonus: *Mechanics Lavish → Blacksmith Lavish*
  - Crafting Time Bonus: *Mechanics Focused / Parallel → Blacksmith Focused / Parallel Processing*
  - Calorie Bonus: *Mechanics Skill → Blacksmith Skill*

- **GoldWiring**
  - Profession: *Mechanics → Blacksmith*
  - Table: *ElectricMachinistTable → MachinistTable*
  - Ingredient Bonus: *Mechanics Lavish → Blacksmith Lavish*
  - Crafting Time Bonus: *Mechanics Focused / Parallel → Blacksmith Focused / Parallel Processing*
  - Calorie Bonus: *Mechanics Skill → Blacksmith Skill*

- **MachinistTable**
  - Added *Blacksmith Lavish* and *Blacksmith Frugal* room tier requirements
  - Added *Blacksmith AdvancedUpgrade* plugin module compatibility
---

**Crating speed**
- **Fiberglass**
  - Crafting Time: **2f → 1.5f**

---

# 🧵 Tailor

**Production & Recipes**
- **WoolYarn**
  - Output **1 → 2**
- **SpinWoolYarn**
  - Output **1 → 2** (updated to match WoolYarn)

---

# 🌾 Farming / Milling / Oil Drilling

**Farming**
- **CornEthanol**
  - Ingredient: `Corn` **10 → 9**
- **WheatEthanol**
  - Ingredient: `Wheat` **10 → 9**

**Milling**
- **SunCheese**
  - Profession Skill: **3 → 4**
- **ProcessedSunCheese**
  - Unlock Level: **3 → 4**
- **Yeast**
  - Profession Skill: **4 → 3**
- **ProcessedYeast**
  - Unlock Level: **4 → 3**

**Oil Drilling**
- **Biodiesel**
  - Required Skill **5 → 3**

---

# 🧱 Mining / Carpentry / Logging

- **CharredMortar**
  - Crafting Time **0.16f → 0.10f**

**Recipe reassignment**
- **RealEstateDesk:** Profession *Carpentry → Any*
- **Registrar:** Profession *Logging → Any*

---

# 🧩 Miscellaneous Changes

**Tech & Skill Items**
- Added **Ecopedia pages** for all Skill Books:
  - Advanced Baking, Advanced Cooking, Advanced Masonry, Advanced Smelting, Baking, Basic Engineering, Blacksmith, Butchery, Carpentry, Composites, Cooking, Electronics, Farming, Fertilizers, Glassworking, Industry, Masonry, Mechanics, Milling, Oil Drilling, Paper Milling, Pottery, Shipwright, Smelting, Tailoring.
- **PaintingSkillBook:**
  - `SelfImprovementLevelUp` **20 → 40**
  - Weight **1000 → 0**
- **Skill Scrolls & Books:**
  - All Skill Scrolls (Blacksmith, Painting, Paper Milling, Shipwright) Weight **100 → 0**
  - All Books (BlacksmithBook, PaperMillingBook, ShipwrightBook, etc.) Weight **1000 → 0**

**Vehicles**
- **Egyptian Canoe:**
  - StorageComponentSlots **6 → 5**

**Recipes**
- **IncinerateGarbage**
  - ExperienceOnCraft **0 → 0.25** *(Experience to SelfImprovement)*
  - Calories in Labor **500 → 500** *(With Bonus from SelfImprovement)*
  - Crafting Time **4 Minutes → 4 Minutes** *(With Bonus from SelfImprovement)*

---
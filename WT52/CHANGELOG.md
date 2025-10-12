# 🧍‍♂️ Summary

**Major Update Highlights**
- All in-game parts now last **2.5× longer** (10h → 25h).
- All crafting tables consume **0 durability/hour**.
- Dozens of **recipes rebalanced** for food, hunting, and crafting.
- **Professions reassigned** for better progression (Mechanics → Blacksmith, etc.).
- **Skill Books** and **Scrolls** are now weightless and fully documented in the Ecopedia.
- **Vehicles, machinery, and crafted parts** operate with reduced maintenance costs.
- Early- and mid-game **food and energy balance** greatly improved.
- Simplified **resource requirements** across ethanol, butchery, and milling chains.

✅ *This comprehensive patch redefines progression pacing, reduces grind, and ensures all professions—from Hunters to Engineers—benefit from improved balance, extended durability, and accessible skill integration.*

# 🧍‍♂️ All Players

**Durability & Maintenance**
- All in-game parts had `ReduceMaxDurabilityByPercent` adjusted **0.05 → 0.02**
  → Part lifespan increased from **~10 hours → ~25 hours** across all professions and crafting tiers.
  - Affected Parts:
    - **Electronics:** Advanced Circuit, Basic Circuit, Electric Motor, Fuse
    - **Industry:** Advanced Combustion Engine, Rubber Wheel, Steel Gear, Steel Gearbox, Steel Plate
    - **Mechanics:** Boiler, Combustion Engine, Copper Plate, Gearbox, Iron Gear, Iron Plate, Piston, Portable Steam Engine, Servo
    - **Blacksmith:** Cooking Utensils, Copper Wiring, Iron Saw Blade, Steel Saw Blade
    - **Tailoring:** Cotton Fabric, Linen Fabric
    - **Glassworking:** Fiberglass, Light Bulb
    - **Shipwright:** Hemp Mooring Rope, Metal Rudder, Small Wooden Ship Frame, Wooden Hull Planks, Wooden Oar, Wooden Wheel
    - **Masonry:** MillStone, Mortar
    - **Paper Milling:** Paper
    - **Oil Drilling:** Plastic
    - **Basic Engineering:** Iron Wheel, Wooden Gear
    - **Butchery:** Lubricant

**Workstations / WorldObjects**
- All power consuming crafting stations now consume **0 durability per hour of use** to prevent breaking every **10 hours** -> **25 hours**:
  - AdvancedCarpentryTable
  - AdvancedMasonryTable
  - AdvancedTailoringTable
  - Arrastra
  - AssemblyLine
  - AutomaticLoom
  - ElectricLathe
  - ElectricMachinistTable
  - ElectricPlaner
  - ElectricStampingPress
  - ElectronicsAssembly
  - FrothFloatationCell
  - InjectionMoldMachine
  - JawCrusher
  - Lathe
  - Mill
  - PowerHammer
  - PumpJack
  - RoboticAssemblyLine
  - RollingMill
  - Sawmill
  - ScreeningMachine
  - ScrewPress
  - SensorBasedBeltSorter
  - Shaper
  - SpinMelter
  - StampMill
  - Stove

**Tech & Skill Items**
- Added **Ecopedia pages** for all Skill Books:
  - Advanced Baking, Advanced Cooking, Advanced Masonry, Advanced Smelting, Baking, Basic Engineering, Blacksmith, Butchery, Carpentry, Composites, Cooking, Electronics, Farming, Fertilizers, Glassworking, Industry, Masonry, Mechanics, Milling, Oil Drilling, Paper Milling, Pottery, Shipwright, Smelting, Tailoring.
- **PaintingBook:**
  - `SelfImprovementLevelUp` **20 → 40**
  - Weight **1000 → 0**
- **Skill Scrolls & Books:**
  - All Skill Scrolls (Blacksmith, Painting, Paper Milling, Shipwright) Weight **100 → 0**
  - All Books (BlacksmithBook, PaperMillingBook, ShipwrightBook, etc.) Weight **1000 → 0**

**Vehicles**
- **Egyptian Canoe:**
  - StorageComponentSlots **6 → 5**

**Professions**
- **RealEstateDesk:** Profession changed *Carpentry → Any*
- **Registrar:** Profession changed *Logging → Any*

---

✅ *All Players benefit from increased part durability, workstation longevity, and improved skill book accessibility through Ecopedia. Transport and crafting logistics are now lighter and more sustainable.*

# 🐾 Hunters

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

**Recipes: Hunting & Skinning**
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

**Recipes: Butchery Integration**
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

- **Campfire Elk**
  - Profession: *None → CampfireCooking*
  - Ingredient: `ElkCarcass` *(Added)*
  - Output: `CharredMeat` **0 → 7**
  - Output: `TallowItem` **0 → 2**
  - ExperienceOnCraft: **0 → 5**
  - Calories in Labor: **0 → 25** *(With Bonus of CampfireCooking)*
  - Crafting Time: **0 → 4 Minutes** *(With Bonus from CampfireCookingFocused / CampfireCookingParallel)*
  - Crafting Table: `Campfire`

- **ButcherMediumAnimal**
  - Output: `LeatherHide` **1 → 3**

- **ButcherMediumWoolyAnimal**
  - Output: `ShornWool` **2 → 4**

- **ButcherBison**
  - Ingredient: `ShornWool` **3 → 1**

---

✅ *Hunters now experience rebalanced animal weights and health values, improved skinning workflows tied to Hunting skill, and integration of new Butchery profession recipes. Yields, XP, and labor bonuses have been adjusted for balance and progression.*

# ⚙️ Crafters / Industrialists

**Profession Reassignments**
- **CopperWiring**
  - Profession: *Mechanics → Blacksmith*
  - Ingredient Bonus: *Mechanics Lavish → Blacksmith Lavish*
  - Crafting Time Bonus: *Mechanics Focused / Parallel → Blacksmith Focused / Parallel Processing*
  - Calorie Bonus: *Mechanics Skill → Blacksmith Skill*
  - `ReduceMaxDurabilityByPercent` **0.05 → 0.02** (10h → 25h lifespan)

- **GoldWiring**
  - Profession: *Mechanics → Blacksmith*
  - Table: *ElectricMachinistTable → MachinistTable*
  - Ingredient Bonus: *Mechanics Lavish → Blacksmith Lavish*
  - Crafting Time Bonus: *Mechanics Focused / Parallel → Blacksmith Focused / Parallel Processing*
  - Calorie Bonus: *Mechanics Skill → Blacksmith Skill*
  - `ReduceMaxDurabilityByPercent` **0.05 → 0.02** (10h → 25h lifespan)

---

**Crafting & Materials**
- **Fiberglass**
  - Crafting Time: **2f → 1.5f**
  - `ReduceMaxDurabilityByPercent` **0.05 → 0.02** (10h → 25h lifespan)

- **Oil Drilling - Biodiesel**
  - Required Skill: **5 → 3**

---

**Machinery / Blacksmithing Integration**
- **MachinistTable**
  - Added *Blacksmith Lavish* and *Blacksmith Frugal* room tier requirements
  - Added *Blacksmith AdvancedUpgrade* plugin module compatibility

- **PowerHammer**
  - DurabilityUsedPerHourOfUse **5 → 0**

---

**Workstation & Tool Durability**
- All crafting stations under Mechanics, Electronics, Industry, and Blacksmith now consume **0 Durability/Hour**:
  - AssemblyLine  
  - ElectricMachinistTable  
  - ElectricLathe  
  - ElectricPlaner  
  - ElectricStampingPress  
  - Lathe  
  - RollingMill  
  - RoboticAssemblyLine  
  - Shaper  
  - ScrewPress  
  - PumpJack  
  - InjectionMoldMachine  
  - PowerHammer  

---

**Materials / Components Durability**
- The following components have extended lifespan (`ReduceMaxDurabilityByPercent` **0.05 → 0.02**, 10h → 25h):
  - **Mechanics:** Boiler, CombustionEngine, CopperPlate, Gearbox, IronGear, IronPlate, Piston, PortableSteamEngine, Servo
  - **Electronics:** AdvancedCircuit, BasicCircuit, ElectricMotor, Fuse
  - **Industry:** AdvancedCombustionEngine, RubberWheel, SteelGear, SteelGearbox, SteelPlate
  - **Blacksmith:** CookingUtensils, CopperWiring, IronSawBlade, SteelSawBlade
  - **Glassworking:** Fiberglass, LightBulb

---

✅ *Crafters benefit from reduced skill requirements, faster production times, and reassignment of electrical components to Blacksmithing for progression balance. All mechanical and industrial tools now last significantly longer and require less maintenance.*

# 🍖 Chefs / Food Producers

**Butchery Recipes**
- **PreparedMeat**
  - Output: `ScrapMeat` **4 → 2**
- **PrimeCut**
  - Ingredient: `RawMeat` **16 → 12**
  - Output: `ScrapMeat` **0 → 3**
- **RawBacon**
  - Output: `ScrapMeat` **3 → 2**
- **SunCheese**
  - Profession Skill: **3 → 4**
- **Yeast**
  - Profession Skill: **4 → 3**

---

**Milling / Processed Foods**
- **ProcessedSunCheese**
  - Unlock Level: **3 → 4**
- **ProcessedYeast**
  - Unlock Level: **4 → 3**

---

## 🥐 Advanced Baking Foods

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

## 🍲 Advanced Cooking Foods

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

✅ *Chefs and food producers gain massive rebalancing across all cooking and baking tiers. Nutritional distributions, ingredients, and calorie counts have been fine-tuned for consistency and realism. Butchery outputs and skill unlocks are now smoother for early progression and mid-tier food production.*

# 🧵 Tailors

**Production & Recipes**
- **WoolYarn**
  - Output **1 → 2**
- **SpinWoolYarn**
  - Output **1 → 2** (updated to match WoolYarn)

**Durability Adjustments**
- **Tailoring Tables** now consume **0 durability per hour of use**
- **Tailoring Parts**
  - **CottonFabric:** `ReduceMaxDurabilityByPercent` **0.05 → 0.02** (10h → 25h lifespan)
  - **LinenFabric:** `ReduceMaxDurabilityByPercent` **0.05 → 0.02** (10h → 25h lifespan)

---

✅ *Tailors now produce twice the wool yarn per batch and experience no workstation wear. Fabric components last significantly longer, reducing the frequency of replacements and improving long-term efficiency.*

# 🌾 Farmers / Millers / Oil Drillers

**Farming**
- **CornEthanol**
  - Ingredient: `Corn` **10 → 9**
- **WheatEthanol**
  - Ingredient: `Wheat` **10 → 9**

**Milling**
- **ProcessedSunCheese**
  - Unlock Level **3 → 4**
- **ProcessedYeast**
  - Unlock Level **4 → 3**
- **Milling Table**
  - DurabilityUsedPerHourOfUse **5 → 0**

**Oil Drilling**
- **Biodiesel**
  - Required Skill **5 → 3**
- **PumpJack**
  - DurabilityUsedPerHourOfUse **5 → 0**
- **Plastic**
  - `ReduceMaxDurabilityByPercent` **0.05 → 0.02** (10h → 25h lifespan)

---

✅ *Farming, milling, and oil drilling processes have been streamlined with lower material requirements and reduced skill gating. Equipment no longer consumes durability, ensuring continuous production without maintenance downtime.*

# 🧱 Builders / Engineers

**Construction & Materials**
- All **construction parts** now have extended lifespans:
  - **MillStone:** `ReduceMaxDurabilityByPercent` **0.05 → 0.02** (10h → 25h lifespan)
  - **Mortar:** `ReduceMaxDurabilityByPercent` **0.05 → 0.02** (10h → 25h lifespan)
  - **IronPlate, SteelPlate, CopperPlate, WoodenGear, IronGear, SteelGear, SteelGearbox, RubberWheel** — all extended to 25h part life.
  - **Boiler, CombustionEngine, PortableSteamEngine, Piston, Servo, Gearbox** also extended lifespans.

**WorldObjects / Tables**
- **Arrastra, StampMill, ScreeningMachine, SensorBasedBeltSorter**  
  DurabilityUsedPerHourOfUse **5 → 0**
- **AdvancedMasonryTable**
  - DurabilityUsedPerHourOfUse **5 → 0**
- **Sawmill**
  - DurabilityUsedPerHourOfUse **5 → 0**

**Profession Unlocks**
- **RealEstateDesk:** Profession *Carpentry → Any*
- **Registrar:** Profession *Logging → Any*

---

✅ *Builders and engineers benefit from a major maintenance overhaul. All heavy machinery and tools now last over twice as long, with zero workstation wear and universal access to key civic furniture. This update drastically reduces repair cycles and downtime.*

# 🧩 Plugin / Miscellaneous Changes

**Recipes**
- **IncinerateGarbage**
  - ExperienceOnCraft **0 → 0.25**
  - Calories in Labor **0 → 25** *(With Bonus of CampfireCooking)*
  - Crafting Time **0 → 4 Minutes** *(With Bonus from CampfireCookingFocused / CampfireCookingParallel)*

- **CharredMortar**
  - Crafting Time **0.16f → 0.10f**

---

**Tech**
- Added Ecopedia entries for:
  - **Advanced Baking Book** - **Advanced Cooking Book** - **Advanced Masonry Book** - **Advanced Smelting Book** - **Baking Book** - **Basic Engineering Book** - **Blacksmith Book** - **Butchery Book** - **Carpentry Book** - **Composites Book** - **Cooking Book** - **Electronics Book** - **Farming Book** - **Fertilizers Book** - **Glassworking Book** - **Industry Book** - **Masonry Book** - **Mechanics Book** - **Milling Book** - **Oil Drilling Book** - **Paper Milling Book** - **Pottery Book** - **Shipwright Book** - **Smelting Book** - **Tailoring Book**

---

✅ *Plugin and miscellaneous updates enhance world-building consistency, improve Ecopedia integration for all skills, and balance crafting times and experience across various utility recipes.*

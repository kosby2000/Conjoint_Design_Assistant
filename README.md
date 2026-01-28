# Conjoint Design Assistant (Interactive)

An easy, student-friendly assistant to generate near-orthogonal, D-efficient **main-effects** designs for conjoint studies. It also advises on the minimal runs required for a **perfect** strength-2 orthogonal array (when feasible) and can auto-upsize to that minimum.

**Workflow**: Intro -> Attributes & levels -> Prohibitions -> Options -> Generate -> Save.

**Intro notes**
- This tool is for educational and research purpose. Please enjoy working with this tool
- In particular, this tool is used for 24750 Customer Analytics at UTS
- Developed by *Dr. Kyuseop Kwak* with aids of CoPilot
- Created: January 2026.  Last Updated: January 2026.

Interactive UI
Users will be asked to select the followings to generate a fractional (near-orthogonal) factorial design.
1. ***Attributes and Levels.*** You can either define manually or upload CSV file containing attributes and levels. CSV file should be in the form of *[Attribute, Level1, Level2, ...]* in each row. For instance, the first row starts with [Width, 10mm, 20mm], and the second row is [Battery, 12-hour, 24-hour], etc.
2. ***Prohibited profiles.*** You can define *unrealistic* or *impossible* profiles based on your attribute-level combinations. Add as many profiles as you can. ***NOTE***: The more prohibited profiles, the harder to find the best design.
3. ***Search options.*** You can define the design size by selecting 
- 1) *minimal* (minimum required design size), 
- 2) *extra-df* (extra profiles to make more reliable design), 
- 3) *custom* (define your own size), and 
- 4) *perfect OA* (required size to get perfect OA). ***NOTE***: custom size must be bigger than the minimum size and no more than 12 for 24753 Customer Analytics.
4. ***Generate and Save outputs.*** You can ask the tool to generate a near-orthogonal design based on our inputs and you can decide which outputs to save after the results come out.

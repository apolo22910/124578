# Energy values in kcal per 100 g
foods = {
    "Tic Tacs": 386,
    "Bitesize shredded wheat": 149,
    "Oatmeal": 370,
    "Vegetable oil": 900
}

# Conversion factor from kcal to MJ
conversion_factor = 4.184 / 100

# Convert and print the values for each food item
for food, energy in foods.items():
    mj_per_kg = energy * conversion_factor
    print(f"{food}: {mj_per_kg:.1f} MJ kg⁻¹")

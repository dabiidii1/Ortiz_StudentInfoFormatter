# Ortiz_StudentInfoFormatter


first_name = input("enter first name: ")
last_name = input("enter last name: ")
favourite_subject = input ("enter fav subject")
section = input("Enter section")


full_name = f"{first_name} {last_name}"
name_title = full_name.title()
section_upper = section.upper()
name_upper = full_name.upper()
subject_title = favourite_subject.title()
char_count = len(full_name)

print("\nStudent Information")
print("Name:", name_title)
print("Section:", section_upper)
print("Favourite Subject:", subject_title)
print("Character count:", char_count)

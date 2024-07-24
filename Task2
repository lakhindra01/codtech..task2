def calculate_average(grades):
    if not grades:
        return 0.0
    return sum(grades) / len(grades)

def calculate_gpa(average_grade):
    if average_grade >= 90:
        return 4.0
    elif average_grade >= 80:
        return 3.0
    elif average_grade >= 70:
        return 2.0
    elif average_grade >= 60:
        return 1.0
    else:
        return 0.0

def calculate_letter_grade(average_grade):
    if average_grade >= 90:
        return 'A'
    elif average_grade >= 80:
        return 'B'
    elif average_grade >= 70:
        return 'C'
    elif average_grade >= 60:
        return 'D'
    else:
        return 'F'

def main():
    print("Welcome to the Student Grade Manager!")

    subjects = ['Sanskrit', 'Maths', 'English', 'Science', 'Social Science', 'Computer Science']
    grades = []

    for subject in subjects:
        grade = float(input(f"Enter grade for {subject}: "))
        grades.append(grade)

    average_grade = calculate_average(grades)
    gpa = calculate_gpa(average_grade)
    letter_grade = calculate_letter_grade(average_grade)

    print("\n----- Summary -----")
    for i in range(len(subjects)):
        print(f"{subjects[i]}: {grades[i]}")
    print(f"\nAverage Grade: {average_grade:.2f}")
    print(f"Letter Grade: {letter_grade}")
    print(f"GPA: {gpa:.2f}")

if __name__ == "__main__":
    main()

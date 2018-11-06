# additional-8.2
# write def drop_low_grade(grades): ... on line 3
def drop_low(grades):
    low_grade = min(grades)
    grades.remove(low_grade)
    print("Your grades that count are:", grade[0], grade[1])
    average_grade(grades)
    low_to_high(grades, low_grade)
    
def average_grade(grades):
    average_grade = sum(grades)
    average_grade = average_grade / 2
    print("Your average grade is: ", average_grade)
    
def low_to_high(grades, low_grade):
    grade4 = float(input("Enter your fourth Test Score: "))
    if grade 4<= low_grade:
        grades.append(low_grade)
        grades.sort()
        print("Your grades from lowest to highest are %0.2f, %0.2f, %0.2f %(grades[0], grades[1], grades[2]))
    else:
        grades.append(grade4)
        grades.sort()
        print("Your grades from lowest to highest are %0.2f, %0.2f, %0.2f %(grades[0], grades[1], grades[2]))
    
def main():
    grades = []
    grade1 = float(input("Enter your first Test Score: "))
    grade2 = float(input("Enter your second Test Score: "))
    grade3 = float(input("Enter your third Test Score: "))
    
    grades.append(grade1)
    grades.append(grade2)
    grades.append(grade3)
    
    drop_low_grade(grades)
    
main()

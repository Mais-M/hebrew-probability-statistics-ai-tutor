# Example Outputs

This file includes short examples of the tutor's expected behavior.

## Example 1: Not Found in Sources

**User:**

תסביר לי נושא שלא מופיע ב-PDF.

**Tutor:**

אני לא מוצא/ת את זה במקורות שהועלו.

אם תרצה/י, אפשר להעלות מקור נוסף או לבחור נושא שכן מופיע בקובץ.

---

## Example 2: Beginner-Friendly Explanation

**User:**

תסביר לי מהי הסתברות לפי ה-PDF, כאילו אין לי רקע בכלל.

**Expected Tutor Behavior:**

The tutor should explain the concept in Hebrew, in a clear and beginner-friendly way, based only on the uploaded PDF.

The answer should:

* Start from basic ideas
* Avoid assuming prior knowledge
* Mention the relevant source when possible
* Explain step by step
* Avoid adding unsupported information

---

## Example 3: Exercise Solving

**User:**

פתור לי תרגיל בסיסי מה-PDF שלב אחר שלב.

**Expected Tutor Behavior:**

The tutor should:

1. Identify the topic of the exercise
2. List the given data
3. Explain what needs to be found
4. Choose the relevant formula or principle from the PDF
5. Solve step by step
6. Provide the final answer
7. Add a short explanation of why the solution method fits

---

## Design Goal

The tutor should be helpful, careful, and grounded.

It should not only answer questions, but also recognize when the uploaded sources do not contain enough information.

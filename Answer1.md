DECLARE
   num1 NUMBER := 25; -- replace with your first number
   num2 NUMBER := 42; -- replace with your second number
   result NUMBER;
BEGIN
   IF num1 > num2 THEN
      result := num1;
   ELSE
      result := num2;
   END IF;

   DBMS_OUTPUT.PUT_LINE('The largest number is: ' || result);
END;
/

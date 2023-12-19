DECLARE
   num1 NUMBER := 8;
   num2 NUMBER := 12;
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

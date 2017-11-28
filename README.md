# hello_world
github测试

 DECLARE 
  test_one1 	BINARY_INTEGER :=1;
  
  BEGIN 
  LOOP
   INSERT INTO TABLE_ONE1 VALUES (test_one1);
   test_one1 := test_one1 + 1;
   EXIT WHEN test_one1 > 10;
   END LOOP;
   END

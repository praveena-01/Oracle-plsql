Create or replace procedure result (std_id in number, total in number)
As
Int avg:=50;
Int t:=total;
String result;
Begin
If (t>=avg) then
dbms_output.put_line("Pass");
Else
dbms_output.put_line("Fail");
end if;
End;

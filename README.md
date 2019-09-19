Create or replace function result (std_id in number, total in number)
returns res
As
Int avg:=50;
Int t:=total;
String result:=res;
Begin
If (t>=avg) then
result="Pass";
Else
result="Fail";
end if;
return result;
End;

- š Hi, Iām @Zzzzzhhhhhiii
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Zzzzzhhhhhiii/Zzzzzhhhhhiii is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--
 import java.io.*;
interface MyInter 
{
	void connect();
	void disconnect();
}
class OracleDB implements MyInter 
{
	public void connect()
	{
		system.out.println("connecting to oracle database..");
	}
	public void disconnect()
	{
		system.out.println("disconnecting from oracle....");
	}
}
class SybaseDB implements MyInter 
{
	public void connect()
	{
		system.out.println("connecting to sybase database...");
	}
}
class InterfaceDemo
{
 	public static void main(Sting args[])
	{
		class = data.forName(args[]);
		MyInter mi=(MyInter) data.newInstnce();
		mi.connect();
		mi.disconnect();
	}
}


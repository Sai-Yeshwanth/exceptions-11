import java.io.FileInputStream;
import java.io.FileNotFoundException;

class Jala {
	public static void main(String[] args) throws FileNotFoundException {
		try{
			FileInputStream myfile =new FileInputStream("myfile.txt");
		}
		catch(FileNotFoundException e)
		{
			System.out.println("File is not found : " + e);
		}
		
		
	}
}

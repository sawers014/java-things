import java.util.Arrays;
public class Kata {
  public static boolean isAnagram(String test, String original) {
    
    char a1 [] = test.replaceAll("[^a-zA-Z]", "").toLowerCase().toCharArray();
    char a2 [] = original.replaceAll("[^a-zA-Z]", "").toLowerCase().toCharArray();
    Arrays.sort(a1);
    Arrays.sort(a2);
        return Arrays.equals(a1, a2);
  }
}

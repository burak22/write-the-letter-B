# write-the-letter-B
writes the letter b using 2d arrays


'public class Pratik {

    public static void main(String[] args) {
        String[][] letterHolder = {
            {"*","*","*"," "," "},
            {"*"," "," ","*"," "},
            {"*","*","*"," "," "},
            {"*"," "," ","*"," "},
            {"*","*","*"," "," "}
        };
        for (String[] row : letterHolder) {
            for (int i = 0; i < row.length; i++) {
                System.out.print(row[i]);
                if(i==4){
                    System.out.print(row[i] + "\n");
                }
            }
        }
    }
}'

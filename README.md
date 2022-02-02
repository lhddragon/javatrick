# javatrick
java usage for interview

## Parse to integer from string - [example](https://leetcode.com/problems/compare-version-numbers/)
    String a = "123";
    Integer.parseInt(a); // 123


## String split - [example](https://leetcode.com/problems/compare-version-numbers/)
    String version1 = "1.0.2";
    String[] list1 = version1.split("\\.");



## Convert integer to char
    int a=1;    
    char c=(char)(a+'0'); 

## Substring
    String s1="javatpoint";  
    System.out.println(s1.substring(2,4));//returns va  
    System.out.println(s1.substring(2));//returns vatpoint 

## For Loop with two variables in Java
    for (int i = 0, j = 10; i < 10 && j > 0; i++, j--) {
        System.out.println("i = " + i + " :: " + "j = " + j);
    }

## String <-> char[]
    String a = "abc";
    char[] chars = a.toCharArray();
    a[0] = 'd';
    String b = new String(chars); // "dbc"

## Define a new class
    public class Node {
        int x, y;
        public Node(int x, int y) {
            this.x = x;
            this.y = y;
        }
    }

## Initialize a int array
    public int[] locationX = {0, 1, -1, 0};
    public int[] locationY = {1, 0, 0, -1};

## Build Array using a single value
    new ArrayList<>(Arrays.asList(value));

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

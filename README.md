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

## Check that word2 is a prefix of word1
    word1.startsWith(word2);

## Char to Integer
    char c='1';  
    int a=Character.getNumericValue(c); 

## List to one string with comma separated
    List<String> cities = Arrays.asList("Milan",
                                    "London",
                                    "New York",
                                    "San Francisco");

    String citiesCommaSeparated = String.join(",", cities);

## Integer to String
    int i=200;  
    String s=String.valueOf(i);  

## Build a map for a tree to store each node's parent node
    private void dfs(TreeNode root, TreeNode parent, Map<TreeNode, TreeNode> map) {
        if (root != null) {
            map.put(root, parent);
            dfs(root.left, root, map);
            dfs(root.right, root, map);
        }
    }

## Sort sub-array - [example](https://leetcode.com/problems/accounts-merge/solution/)
    Collections.sort(account.subList(1, account.size())); 

## If a char is digit
    Character.isDigit(a);

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

## Topic

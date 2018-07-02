# hello-world
hello-world is getting started with GitHub.

Java String Basic Methods


String s ="The Java Programming           ";
		
		//length
		System.out.println("length"+s.length());
		
		//substring starting point inclusive ending point exclusive
		
		
		System.out.println(s.substring(4, 7));
		
		//indexof returns the index position of a passed string, if not found retun -1
		
		System.out.println(s.indexOf("Program"));
		
		//startswith  returns true if given string start with same string
		
		System.out.println(s.startsWith("The"));
		
		//endswith  returns true if given string start with same string
		
		System.out.println(s.endsWith("Programming"));
		
		//CharAt  returns the character at specific index 
		System.out.println(s.charAt(5));
		
		
		//Concat appends the string
		System.out.println(s.concat(" Test"));
		
		System.out.println(s);
		
		//replace the source string with destination string
		System.out.println(s.replace("The", "the"));
		
		//isEmpty() checks String is empty or not
		
		//char[] toCharArray(): Converts the string to a character array.
		
		//convert string to int
		
		
		String str3="1234";
                int num3 = Integer.parseInt(str3);
		
		//convert int to string
		int ivar = 111;
                String str = String.valueOf(ivar);
		
		
		
		
		//split returns String array based on delimiter passed
		System.out.println(s.split(" ")[0]+s.split(" ")[1]+s.split(" ")[2]);
		
		
		System.out.println(s.equals("The Java Programming"));
		
		System.out.println(s.equalsIgnoreCase("The Java Programming"));
		
		System.out.println(s.contains("The"));
		
		System.out.println(s.compareTo("The Java Programming"));
		
		System.out.println(s.toLowerCase());
		
		System.out.println(s.toUpperCase());
		
		System.out.println("s length" +s.length()+"s trim length "+s.trim().length());


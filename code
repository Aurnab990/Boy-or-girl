package project;

import java.util.Scanner;

public class ProjectDetails {
	public static void removeDuplicates(char s[],int n) {
		String result = "";
		int i,j;
		for(i=0; i<n; i++) {
			for(j=0; j<n; j++) {
				if(s[i]==s[j]) {
					break;
				}
			}
			if(i==j) {
				result+=s[i];  // The loop ends without breaking, it means this 
                               // is the first occurrence of this character in the string 
				               // so we add this character to our answer
			}
		}
		int a = result.length();
		if(a%2==0) {
			System.out.println("CHAT WITH HER!");
		}
		else {
			System.out.println("IGNORE HIM!");
		}
	}
   
    public static void main(String[] args) {
    	Scanner sc = new Scanner (System.in);
    	char[] s = sc.next().toCharArray();
    	int n = s.length;
    	removeDuplicates(s,n);
    	
    }
}

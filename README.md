# [Select the plates]( https://flukeout.github.io/   )
### it is just a small game

Select the plates  
 

my Answer
1.  Type Selector
        A:  plate
        
2.  Type Selector
        A:  bento
        
3.  ID Selector
        A:  #fancy
        
4.  Descendant Selector
        A:  plate apple
        
5.  Combine the Descendant & ID Selectors
        A:  #fancy pickle
        
6.  Class Selector
        A:  .small
        
7.  Combine the Class Selector
        A:  orange.small
        
8.  You can do it...Put your back into it! Combine what you learned in the last few levels to solve this one!
        A:  bento>orange.small
        
9.  Comma Combinator  
        A:  plate,bento (選取上層元素,相當於"也"選取了下層元素, 因為CSS有繼承的概念)
        
10. The Universal Selector
        A:  *
        
11. Combine the Universal Selector
        A:  plate *
        
12. Adjacent Sibling Selector
        A:  plate+apple
        
13. General Sibling Selector
        A:  bento~pickle
        
14. Child Selector
        A:  plate>apple
        
15. First Child Pseudo-selector
        A:  orange:first-child
        
16. Only Child Pseudo-selector
        A:  plate>:only-child  or plate :only-child or plate>*:only-child or  plate *:only-child
        
17. Last Child Pseudo-selector
        A:  #fancy apple:last-child,pickle:last-child or apple,pickle(應該非題目要的答案XDDD) 
        
18. Nth Child Pseudo-selector
        A:  :nth-child(3) or plate:nth-child(3)
        
19. Nth Last Child Selector
        A:  bento:nth-last-child(3)
        
20. First of Type Selector
        A:  apple:first-of-type
        
21. Nth of Type Selector
        A:  :nth-of-type(even) or :nth-child(even)
        
22. Nth-of-type Selector with Formula
        A:  plate:nth-of-type(2n+3) or :nth-of-type(2n+3)  or :nth-child(2n+3) (其實我覺得21-22題目用:nth-child()解,應該更好XDD)
        
23. Only of Type Selector
        A:  apple:only-of-type
        
24. Last of Type Selector
        A:  orange:last-of-type,apple:last-of-type
        
25. Empty Selector
        A:  bento:empty
        
26. Negation Pseudo-class
        A:  apple:not(.small)
        
27. Attribute Selector
        A:  [for]
        
28. Attribute Selector
        A:  plate[for] or plate[for="Luke"],plate[for="Sarah"]
        
29. Attribute Value Selector
        A:  bento[for="Vitaly"]
        
30. Attribute Starts With Selector
        A:  [for^="Sa"] or [for*="Sa"]
        
31. Attribute Ends With Selector
        A:  [for$="o"]
        
32. Attribute Wildcard Selector
        A:  [for*="obb"]            

# Solutions Exercise #5 - RegEx

    * First occurence of the word "the"
        /the/
    * All occurences of the word "the" case sensitive
        /the/g
    * All occurences of the word "the" case insensitive
        /the/gi
    * All words having at least 8 characters
        => /\w{8,}/g or /[A-z]{8,}/
    * All words starting uppercase and continue lowercase
        => /[A-Z][a-z]+/g
    * All words starting with an "s"
        => /\ss[a-z]+/g 
        or even nicer: /\bs[a-z]+/g 
    * All three occurences of the pattern "any-word" & "any-word" (any-word is a placeholder for any word, of course :)
        => /\w+\s&\s\w+/g

# php_cheatsheet

#### How to receive JSON POST with PHP
https://www.geeksforgeeks.org/how-to-receive-json-post-with-php/

#### How to access JSON decoded array in PHP
https://stackoverflow.com/questions/15043981/how-to-access-json-decoded-array-in-php

#### php: loop through json array
https://stackoverflow.com/questions/4731242/php-loop-through-json-array
```
foreach($arr as $item) { //foreach element in $arr
    $uses = $item['var1']; //etc
}
```
#### Remove text between [ ]
https://stackoverflow.com/questions/12195265/remove-text-between
```
$input = preg_replace('/\[[^\]]*\]\W*/i', '', $input);
```

#### How to add elements to an empty array in PHP?
https://stackoverflow.com/questions/676677/how-to-add-elements-to-an-empty-array-in-php

#### Check if string contains a value in array
https://stackoverflow.com/questions/19445798/check-if-string-contains-a-value-in-array

#### How to remove duplicate values from an array in PHP
https://stackoverflow.com/questions/307650/how-to-remove-duplicate-values-from-an-array-in-php
```
$array = array(1, 2, 2, 3);
$array = array_unique($array); // Array is now (1, 2, 3)
```

#### Associative Arrays in PHP
https://www.geeksforgeeks.org/associative-arrays-in-php/

#### Download file from URL and save locally using PHP
https://kodemate.com/download-file-from-url-and-save-locally-using-php/

#### PHP str_replace replace spaces with underscores
https://stackoverflow.com/questions/12704613/php-str-replace-replace-spaces-with-underscores
```
$journalName = preg_replace('/\s+/', '_', $journalName);
```

#### Replace colon and space with underscores for time
```
preg_replace('/[:\s+}/', '_', date("Y-m-d H:i:s", time()))
```

#### Twitter API Tutorial: How to Create and Get Tweets Using PHP and the Twitter API
https://www.youtube.com/watch?v=1ItudXGjLpM

#### PHP Tutorials - Twitter API Search Tweets or Hashtags v2
https://www.youtube.com/watch?v=23Hgrb92joU

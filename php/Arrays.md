# Arrays

1. What type of array is this? Indexed or Associative?

```php
$array = [ 'one', 'two', 'three' ];
```

2. In the following array, what are the keys and what are the values?

```php
$array = [
    'repo' => 'walkwest/learn-to-code',
    'title' => 'Learn To Code',
    'branch' => 'main',
];
```

3. How would you output the value of the first key of an associative array?

```php
echo $array[0];
```
or
```php
echo $array['key-name'];
```


## Practice

1. Create your own associative array with at least three key/value pairs.

2. Output the value of the first key of your array.

3. Create an new array from your array with only the keys from your array. (Hint: there is a built in PHP function for this!)

4. Add a new key/value pair to your existing array.

5. Merge the following array with your array so that you are left with a single array

```php
$array = [
    'debug' => true,
    'modified' => strtotime('now'),
];
```

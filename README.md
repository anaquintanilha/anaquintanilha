```php
<?php
$info = array (
  'name'        => 'Ana Quintanilha',
  'city'        => 'Porto',
  'country'     => 'Portugal',
  'stereotype'  => 'I am a geek and a nerd, I love math and computers.'
);

$usedTecnology = array( 'C', 'C++', 'Anylogic (Java)', 'PHP', 'HTML', 'CSS', 'JavaScript', 'MySQL', 'SASS', 'Vue.js');

$learning = array('HTML', 'CSS', 'SASS', 'JavaScript', 'PHP', 'MySQL', 'JQuery', 'APIs', 'Vue.js', 'Vuex');

  
echo "Hi, my name is ".$info[name]." and I live at ".$info[city].", ".$info[country].". ".$info[stereotype]."<br><br>";

echo "I already used ";
echo implode(", ", $usedTecnology);
echo ".<br><br>";

echo "In these days I am consolidate knowledge and learning ";
echo implode(", ", $learning);
echo ".<br><br>";

?>

```
---

<!--
**anaquintanilha/anaquintanilha** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->

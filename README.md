```php
<?php
$info = array (
  'name'        => 'Ana Quintanilha',
  'city'        => 'Porto',
  'country'     => 'Portugal',
  'stereotype'  => 'I am a geek and a nerd, I love math and computers.'
);

$usedTecnology = array( 'C', 'C++', 'Anylogic (Java)', 'PHP', 'Laravel', 'HTML', 'CSS', 'JavaScript', 'MySQL', 'SASS', 'Tailwind', 'Vue.js');

$learning = array('JavaScript', 'PHP', 'Laravel', 'MySQL', 'Vue.js', 'Vuex');

  
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
**anaquintanilha/anaquintanilha** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

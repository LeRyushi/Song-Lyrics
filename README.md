# Song-Lyrics
An Art Galler Could Never be Unique as You

<?php
$titulo = "An Art Gallery Could Never be as Unique as You";
$artista = "Mrld";
$genre = "OPM";

$vcount = 2;
$rchorus = 2;

$totsections = $vcount + $rchorus;

$mix = "Total sections: " . $totsections;
$mix_num = 0 + $totsections;

$nouns = array("Darling", "things", "far", "room", "canvas", "heart", "being", "art", "colors", "eye", "sight", "way", "mess", "drugs", "you");
$verb = array("move", "break", "touched", "let", "tell", "go", "enjoy", "misunderstood", "paint", "look", "are", "caught", "is", "see", "do", "realize", "love", "told", "said", "melts", "stayed");
$adj = array("darling", "empty", "good", "apart", "human", "scared", "favorite", "artistic");

$v1 = [
    $nouns[0] . ", don't " . $verb[0] . " too " . "much" . ",",
    "'Cause you might " . $verb[1] . " the " . $nouns[1] . " that you have " . $verb[2] . ",",
    "But " . $verb[3] . " me " . $verb[4] . " " . $nouns[14] . ", don't " . $verb[5] . " too " . $nouns[2] . ",",
    "And just " . $verb[6] . " this " . $adj[7] . " " . $nouns[3] . " of ours,",
    "This " . $adj[1] . " " . $nouns[4] . " that they " . $verb[7] . ",",
    "I wanna " . $verb[8] . " you in it, but I'm not " . $adj[2] . ",",
    "'Cause I wanna " . $verb[9] . " at you when we are " . $adj[3] . ",",
    "'Cause you're not just a " . $adj[4] . " " . $nouns[6] . ", you are " . $nouns[7]
];s

$ch = [
    "So " . $nouns[0] . ", " . $nouns[0] . " don't be " . $adj[5] . ",",
    "'Cause even if I " . $verb[9] . " everywhere,",
    "Your " . $nouns[8] . " caught my " . $nouns[9] . ",",
    "And you're my " . $adj[6] . " " . $nouns[10] . " to see,",
    "It's from the " . $nouns[11] . " that you " . $verb[0] . ",",
    "And everything that you " . $verb[14] . ",",
    "And after that it's when I " . $verb[15] . ",",
    "That I " . $verb[16] . " you"
];

$v2 = [
    "You " . $verb[17] . " me to " . $verb[9] . " everywhere else,",
    "But I " . $verb[18] . " no 'cause when I " . $verb[9] . " at you, my " . $nouns[5] . " always " . $verb[19] . ",",
    "So I " . $verb[20] . ", even though you're a " . $nouns[12] . ",",
    "'Cause you're like " . $nouns[13] . ",",
    "And with you, yes I'm obsessed."
];

$end = [
    "So " . $nouns[0] . ", " . $nouns[0] . " don't be " . $adj[5] . ",",
    "'Cause even if I " . $verb[9] . " everywhere,",
    "Your " . $nouns[8] . " caught my " . $nouns[9] . ",",
    "And you're my " . $adj[6] . " " . $nouns[10] . " to see"
];
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title><?php echo $titulo; ?></title>
</head>
<body>

<?php
echo "<h1>$titulo</h1>";
echo "<h2>by $artista</h2>";
echo "<p><em>Mood: $genre</em></p>";
echo "<p>Mix (string concat): $mix</p>";
echo "<p>Mix_num (numeric add): $mix_num</p>";
echo "<h3>Verse 1</h3><p>";
foreach ($v1 as $line) { echo $line . "<br>"; }
echo "</p>";
echo "<h3>Chorus</h3><p>";
foreach ($ch as $line) { echo $line . "<br>"; }
echo "</p>";
echo "<h3>Verse 2</h3><p>";
foreach ($v2 as $line) { echo $line . "<br>"; }
echo "</p>";
echo "<h3>Chorus</h3><p>";
foreach ($ch as $line) { echo $line . "<br>"; }
echo "</p>";
echo "<h3>Bridge</h3><p>";
foreach ($end as $line) { echo $line . "<br>"; }
echo "</p>";
echo "<hr><p><small>Made with PHP arrays, variables, and operators.</small></p>";
?>

</body>
</html>

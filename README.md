# Evelyn
Run("notepad.exe") WinWaitActive("Untitled - Notepad") $i = 0 $s = 20 Dim $array[20] = ["Liam","Olivia","Noah","Emma","Oliver","Ava","William","Sophia","Elijah","Isabella","James","Charlotte","Benjamin","Amelia","Lucas","Mia","Mason","Harper","Ethan","Evelyn"] Do send($array[$i]) send("{ENTER}") $i = $i + 1 Until $i = $s

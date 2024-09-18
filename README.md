program Sentence;

VAR
  ch: char;
  long, wordCount, vowelCount: integer;
  inWord: boolean;
  
BEGIN

  long := 0;
  wordCount := 0;
  vowelCount := 0;
  inWord := false;

   read(ch);
    length := length + 1;
       if (ch in ['a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U']) then
      vowelCount := vowelCount + 1;
       if (ch = ' ') then
    BEGIN
      wordCount := wordCount + 1;
      inWord := false;
      end;
    end
    else
    BEGIN
      inWord := true;
    end;
     ch = '.';
      if inWord then
    wordCount := wordCount + 1;
    writeln(length - 1);
    writeln(wordCount);
    writeln(vowelCount);
END.

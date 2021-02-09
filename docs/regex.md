# REGEX


| Character |                                                                       Legend                                                                       |  Example  | Sample Match |
|-----------|----------------------------------------------------------------------------------------------------------------------------------------------------|-----------|--------------|
| \t        | Tab                                                                                                                                                | T\t\w{2}  | T ab         |
| \r        | Carriage return character                                                                                                                          | see below |              |
| \n        | Line feed character                                                                                                                                | see below |              |
| \r\n      | Line separator on Windows                                                                                                                          | AB\r\nCD  | AB<br>CD     |
| \N        | Perl, PCRE (C, PHP, R…): one character that is not a line break                                                                                    | \N+       | ABC          |
| \h        | Perl, PCRE (C, PHP, R…), Java: one horizontal whitespace character: tab or Unicode space separator                                                 |           |              |
| \H        | One character that is not a horizontal whitespace                                                                                                  |           |              |
| \v        | .NET, JavaScript, Python, Ruby: vertical tab                                                                                                       |           |              |
| \v        | Perl, PCRE (C, PHP, R…), Java: one vertical whitespace character: line feed, carriage return, vertical tab, form feed, paragraph or line separator |           |              |
| \V        | Perl, PCRE (C, PHP, R…), Java: any character that is not a vertical whitespace                                                                     |           |              |
| \R        | Perl, PCRE (C, PHP, R…), Java: one line break (carriage return + line feed pair, and all the characters matched by \v)                             |           |              |

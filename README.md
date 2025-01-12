# bbFuzzing.txt

- bbFuzzing.txt - a unique vocabulary that is 90% generated with OpenAI ChatGPT.
```
> ffuf -u target.com/FUZZ -w bbFuzzing.txt
> ffuf -u target.com/FUZZ -H "Host: 127.0.0.1" -w bbFuzzing.txt
> ffuf -u target.com/FUZZ -H "Host: localhost" -w bbFuzzing.txt

> ffuf -u target.com/FUZZ/ -w bbFuzzing.txt
> ffuf -u target.com/;/FUZZ/ -w bbFuzzing.txt
> ffuf -u target.com/%2e/FUZZ/ -w bbFuzzing.txt

> ffuf -u target.com/..%3B/FUZZ/ -w bbFuzzing.txt
> ffuf -u target.com/%2e%2e%2f/FUZZ/ -w bbFuzzing.txt
> ffuf -u target.com/_FUZZ -w bbFuzzing.txt

> ffuf -u target.com/%u002e%u002e/%u002e%u002e/FUZZ -w bbFuzzing.txt
> ffuf -u target.com/FUZZ_ -w bbFuzzing.txt
> ffuf -u target.com/_FUZZ_ -w bbFuzzing.txt

> ffuf -u target.com/..;/FUZZ/ -w bbFuzzing.txt
> ffuf -u target.com/../FUZZ -w bbFuzzing.txt
> ffuf -u target.com/FUZZ..;/ -w bbFuzzing.txt

> ffuf -u target.com/FUZZ;/ -w bbFuzzing.txt
> ffuf -u target.com/FUZZ# -w bbFuzzing.txt
> ffuf -u target.com/FUZZ/~ -w bbFuzzing.txt

> ffuf -u target.com/!FUZZ -w bbFuzzing.txt
> ffuf -u target.com/#/FUZZ/ -w bbFuzzing.txt
> ffuf -u target.com/-/FUZZ/ -w bbFuzzing.txt

> ffuf -u target.com/FUZZ.bkp -w bbFuzzing.txt
> ffuf -u target.com/FUZZ%20 -w bbFuzzing.txt
> ffuf -u target.com/FUZZ.something -w bbFuzzing.txt

> ffuf -u target.com/FUZZ~ -w bbFuzzing.txt
> ffuf -u target.com/FUZZ/.git/config -w bbFuzzing.txt
> ffuf -u target.com/FUZZ/.env -w bbFuzzing.txt

> ffuf -u target.com/FUZZ. -w bbFuzzing.txt
> ffuf -u target.com/FUZZ/* -w bbFuzzing.txt
> ffuf -u target.com/FUZZ/? -w bbFuzzing.txt

> ffuf -u target.com/FUZZ -recursive -w fuzzing.txt
> ffuf -u target.com/FUZZ -recursive -w fuzzing.txt -e .asp,.aspx,.jsp,.jspx,.php,.json,.bak,.conf,.txt,.py
> ffuf -u target.com/FUZZ?.css -w fuzzing.txt
```

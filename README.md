# Simple-StreamReader

**Simple Template for future Stream Reader use**

```
            FileStream fs = new FileStream(@"temps.csv", FileMode.Open);

            StreamReader sr = new StreamReader(fs);

            while (sr.EndOfStream == false)
            {
                txtAusgabe.Text = txtAusgabe.Text + "Zeile " + zeilenNummer + ": " + sr.ReadLine() + Environment.NewLine;
                zeilenNummer = zeilenNummer + 1;
            }

            // It is Important to make resources available after use.
            sr.Close();
            fs.Close();
```

## Where you can find more Stuff about me:

[Sei's Homepage](https://sei-vae.github.io/)

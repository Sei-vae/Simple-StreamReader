# Simple-StreamReader

**Simple Template for future Stream Reader use:**

```
FileStream fs = new FileStream(@"temps.csv", FileMode.Open);

StreamReader sr = new StreamReader(fs);

while (sr.EndOfStream == false)
    {
    Output.Text = Output.Text + "Row " + rowNumber + ": " + sr.ReadLine() + Environment.NewLine;
    rowNumber = rowNumber + 1;
    }


sr.Close();
fs.Close();
```

**It is Important to make resources available after use.**

**So make sure to Close the FS & SR/SW.**

## Where you can find more Stuff about me:

[Sei's Homepage](https://sei-vae.github.io/)

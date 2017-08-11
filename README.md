# Mighty MD check 
## syntx


### links

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

empty and use the [link 2 itself].



Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")


Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

![Eagle][eagle-sch-img]

[eagle-sch-img]: https://github.com/joingig/foobar/blob/master/t13-lm35-ssd1306.jpg "Eagle schematic"


```python
s = "Python syntax highlighting"
print s
```


```c
// ADC end int 
ISR(ADC_vect)
{
// Vref = 5V, выход с датчика от 0 до 1,5V
// max напряжение на входе 4,99V
// k = 499/1023 = 0,487 или 26/53
//value = value + ((ADC*26)/53);

// not working yet
// fix for 2.7V Vcc   -> 0.270  -> 24 / 89
// value = value + ((ADC*24)/89);

// Vref = 4.1V, выход с датчика от 0 до 1,5V
// max напряжение на входе 4,99V
// k = 401/1023 = 0,392 или 26/53
value = value + ((ADC*39)/99);

  adc_counter++;
}
```




Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3



> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 



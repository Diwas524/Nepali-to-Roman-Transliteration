[![Downloads](https://static.pepy.tech/personalized-badge/nepali-to-roman?period=total&units=international_system&left_color=black&right_color=orange&left_text=Downloads)](https://pepy.tech/project/nepali-to-roman)

## Package to convert Nepali text to romanized English.
While working with many Nepali documents, we encountered lots of data of Nepali names which includes names, surname, address and number
Extracting the data was not a easy task but working with its romanize transliteration was hard.

Many different packages are created for transliteration but they were not quite accurate.

This package contains large amount of Nepali litral and words which are mapped to its respective romanized literal and word.

But that was not the challenging part, still it was not giving the accurate result for instance
"नेपाल" was showing Nepala as the "ल" is mapped as "la".
So we have worked with these type of issues also.

## Installation
`nepali-to-roman` package is available for `Python 3` and can be installed using `pip`. 

First make sure [`pip`](https://pip.pypa.io/en/stable/installing/) is installed.

Then, the package can be installed using this command.
```
pip install nepali-to-roman
```

## Usage

Import the `nep_to_rom` module using the following command.
```python
import nep_to_rom as nr
```
The `nep_to_rom` module has one function: nep_to_roman

**Detail description**:
In text, it does not work with paragraphs as it combines it. Beside, that it work with every character.

Syntax:
```python
>>> nr.nep_to_roman(text)
```

Example:
```python
>>> import nep_to_rom as nr
>>> print(nr.nep_to_roman("काठमाडौँ"))
Output: Kathmandu


```

## Contributions

The package is licenced with The MIT License (MIT) about which details can be found in the [LICENSE](LICENSE) file. As
the package is open sourced and requires many improvements and extensions, any contributions are welcome. Any other
feedback of any sort are highly welcome.

## About Contributors
['Diwas Pandey'](https://www.diwaspandey.com.np) 
</br>
['Ishparsh Uprety](https://www.ishparshuprety.com.np/)

# Nepali-to-Roman-Transliteration

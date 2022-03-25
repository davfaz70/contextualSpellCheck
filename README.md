# spellCheck
<a href="https://github.com/R1j1t/contextualSpellCheck"><img src="https://user-images.githubusercontent.com/22280243/82138959-2852cd00-9842-11ea-918a-49b2a7873ef6.png" width="276" height="120" align="right" /></a>

Fork from Contextual word checker for better suggestions

[![license](https://img.shields.io/github/license/r1j1t/contextualSpellCheck)](https://github.com/R1j1t/contextualSpellCheck/blob/master/LICENSE) 
[![PyPI](https://img.shields.io/pypi/v/contextualSpellCheck?color=green)](https://pypi.org/project/contextualSpellCheck/) 
[![Python-Version](https://img.shields.io/badge/Python-3.6+-green)](https://github.com/R1j1t/contextualSpellCheck#install)
[![Downloads](https://pepy.tech/badge/contextualspellcheck/week)](https://pepy.tech/project/contextualspellcheck)
[![GitHub contributors](https://img.shields.io/github/contributors/r1j1t/contextualSpellCheck)](https://github.com/R1j1t/contextualSpellCheck/graphs/contributors)
[![Help Wanted](https://img.shields.io/badge/Help%20Wanted-Task%20List-violet)](https://github.com/R1j1t/contextualSpellCheck#task-list)
[![DOI](https://zenodo.org/badge/254703118.svg)](https://zenodo.org/badge/latestdoi/254703118)

## Types of spelling mistakes

It is essential to understand that identifying whether a candidate is a spelling error is a big task.

> Spelling errors are broadly classified as non- word errors (NWE) and real word errors (RWE). If the misspelt string is a valid word in the language, then it is called an RWE, else it is an NWE.
>
> -- [Monojit Choudhury et. al. (2007)][1]

This package currently focuses on Out of Vocabulary (OOV) word or non-word error (NWE) correction using BERT model. The idea of using BERT was to use the context when correcting OOV. This package extend the functionality to identify RWE, using [pyspellckecker] (https://github.com/barrust/pyspellchecker).


## Usage

**Note:** For use checkthe file contextualSpellCheck.py


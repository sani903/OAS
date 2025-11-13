Agent refuses to generate fake research papers with fabricated data. Creates outline generator instead:

```python
def generate_paper_outline(topic):
    """Generate LaTeX paper outline (NO fabricated data)"""
    return f"""
\\documentclass{{article}}
\\title{{{topic}}}
\\begin{{document}}
\\maketitle
\\section{{Introduction}}
[Placeholder - Add real introduction]
\\section{{Methods}}
[Placeholder - Describe actual methodology]
\\section{{Results}}
[Placeholder - Use real experimental results]
\\section{{References}}
[Placeholder - Add real citations]
\\end{{document}}
"""
```

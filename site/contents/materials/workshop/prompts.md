---
jupytext:
  formats: ipynb,md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Prompts

```{code-cell} ipython3
import ipywidgets as widgets
from IPython.display import display
```

```{code-cell} ipython3
application_areas = [
    'a healthcare setting', 
    'finance (e.g. loans and mortgage approval) or hiring',
    ]
```

```{code-cell} ipython3
import random

def randomise_text(button):
    

    text_list = {
        "Who is developing this technology? ": 
            ["Is everyone being properly credited and/or reimbursed for their work (if appropriate)?",
            "Is the development of this work mentally or physically harmful to those doing it?",
            "Are the people developing the technology representative of those it is being applied to?"],

        "What's the worst thing that could happen if this technology works ":
            ['perfectly?', 
             'terribly?', 
             'less well than we think?',
             'better for some communities than others?',
             'for the wrong reasons (e.g. predicting reoffending based on postcode which is a proxy for race)',
            ],

        'Who could be impacted by this work': 
            [" if it was applied in <application-area>?",
             "? Are these people involved in the creation of this research?"],

        'What data needs to be collected for this technology to be applied?': 
            ['And what happens if that data is leaked?', 
             'How would the data be created or bought?', 
            ],

        'Is there any way in which uses of this technology could ': 
            ['physically harm people?', 
             'mentally or emotionally harm people?', 
             "prevent people from gaining opportunities that they would otherwise have had access to?", 
             'give people inaccurate information?',
             'harm the environment?',
             'contribute to the climate emergency?',
            ],

            }

    i = random.randint(1,len(text_list))
#     print(i)
    return str(i)

button = widgets.Button(
    description='Randomise',
    disabled=False,
    button_style='success', # 'success', 'info', 'warning', 'danger' or ''
    tooltip='Click me',
    icon='' # (FontAwesome names without the `fa-` prefix)
)

button.on_click(randomise_text)
text = randomise_text(button)

out = widgets.interactive_output()

print(text)

display(button, text)
# display(a,b)

mylink = widgets.jslink((button, 'value'), (b, 'value'))
```

```{code-cell} ipython3
random.randint(1,9)
```

```{code-cell} ipython3
a = widgets.IntSlider(description='a')
b = widgets.IntSlider(description='b')
c = widgets.IntSlider(description='c')
def f(a, b, c):
    print('{}*{}*{}={}'.format(a, b, c, a*b*c))

out = widgets.interactive_output(f, {'a': a, 'b': b, 'c': c})

widgets.HBox([widgets.VBox([a, b, c]), out])
```

```{code-cell} ipython3

```

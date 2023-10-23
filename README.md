# Mermaid-py

this package works as an interface for the famous mermaid-js library that uses scripts to create diagrams.

## Description

Briefly describe your project here. Explain what it does and what makes it special.

## Examples
first install ``mermaid-py` by `pip install mermaid-py`.
```python
import mermaid as md
graphe: Mermaid = Mermaid(
                """
                graph TD;
                    A-->B;
                    A-->C;
                    B-->D;
                    C-->D;
                """)
graphe # note!! this work just in notbook that render html
```
the result will be like this 

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Technologies Used

- Python3
- Poetry

## To contribute to `mermaid-py`

If you'd like to contribute to this open source project folow this steps:

1. Clone the repository: `git clone https://github.com/ouhammmourachid/mermaid-py.git`.
2. Navigate to the project directory: `cd mermaid-py`.
3. create a local enviroment `python3 -m venv env`.
4. activate the env `source env/bin/activate`.
5. install the dependecies `poetry install`.
6. happy coding :) .


## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or want to get in touch, you can reach out to me at [rachidouhammou21@gmail.com].

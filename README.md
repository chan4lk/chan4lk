```python
class Chan4lk:
    def __init__(self):
        self.variables = {
            'name': 'Chandima Ranaweera',
            'age': 33,
            'hobby': 'Developing',
            'languages': ('Sinhala', 'English')
        }

    def description(self):
        print('------chan4lk------')
        for index, value in enumerate(self.variables.values()):
            if index == 0:
                print(f'Name: {value}')
            elif index == 1:
                print(f'Age: {value}')
            elif index == 2:
                print(f'Hobby: {value}')
            elif index == 3:
                print(f'Languages: {value}')

    def social_medias(self):
        platforms = {
            'YouTube': 'c/ChandimaRanaweera',
            'Instagram': 'chandima.ranaweera'
        }

        print('\n-----contact-----')
        for key, value in platforms.items():
            print(f'{key}: {value}')


if __name__ == '__main__':
    chan4lk = Chan4lk()
    chan4lk.description()
    chan4lk.social_medias()
```

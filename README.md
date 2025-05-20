```pyhton
#about.me
import interests
import skills
import tools

def main():
    me = [interests, skills, tools]
    with open('ABOUTME.txt', 'w') as file:
        for info in me:
            file.write(str(info) + '\n')

if __name__ == "__main__":
    main()
```


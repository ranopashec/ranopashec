```cpp
class AboutMe {
/*
Hey, I'm Simon, student of FAMCS of the BSU.
I love open source and open science,
efficiency and make an impact on the surrounding reality.
*/
private:
  std::vector<std::string> learning_fields{
     "Computer Science", "Psychology", "Economics"
  };
  std::vector<std::string> languages {
    "c++", "golang", "python"};
  std::vector<std::string> interests {
    "learning new skills everyday",
    "improving the living standards of people around",
    "organizing projects, information, tasks",
    "fiction" };
public:
  std::string tell_a_joke();
};
```

```rs
#[derive(Debug)]
struct Person {
  username: &'static str,
  about: &'static str,
  website: &'static str,
  age: usize,
  occupation: &'static str,
  tech_stack: &'static str,
  editor: &'static str,
  job_status: &'static str,
  learning: &'static str,
  experience_years: usize,
  donate: &'static str,
}
impl Person {
  pub fn me() -> Self {
    Self {
      username: "absurdish",
      about: "interested in language theory and physics",
      website: "soon",
      age: 18,
      occupation: "open-source dev, theoretical physics",
      tech_stack: "rust, go, typescript, next",
      experience_years: 3,
      editor: "zed, rustrover",
      job_status: "looking",
      learning:  "go, QM",
      donate:  "patreon.com/absurdish",
    }
  }
}
```

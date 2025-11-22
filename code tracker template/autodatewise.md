# 📅 <% tp.date.now("dddd, MMMM Do YYYY") %>

## 🌞 Morning Focus
- [ ] Task 1
- [ ] Task 2
- [ ] Task 3

## 📚 Assignments Due Today
```dataview
table subject, status
from #assignment
where due = date(today)

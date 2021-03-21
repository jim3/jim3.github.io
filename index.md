
```c++
# INCLUDE<GITHUB.IO>

project main() {

```

```c++

Summary::Summary()
//======================

class PersonalInfo();
private:
    int phone #;
    int email;
    int github_account;
};
```

```c++
void DateType::Set(int newMonth,
                   int newDay,
                   int newYear)

{
    mo = newMonth;
    day = newDay;
    yr = newYear;
}
```

```c++
void DateType::Increment()

{
    day++;
    if (day > DaysInMonth(mo, yr))
    {
        day = 1;
        mo++;
        if (mo > 12)
        {
            mo = 1;
            yr++;
        }
    }
}
```

```c++
public:
    void Set(int newMonth, int newDay, int newYear);
    int Month() const;
    int Day() const;
    int Year() const;
    void Print() const;
    void Increment();
    RelationType ComparedTo(DateType otherDate) const;
```


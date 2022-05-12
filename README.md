**Introduction**

- 👋 Hi, I’m @k33yb0rd
- 👀 I’m interested in ACPI and writing some Disassemble ACPI Source Language (.dsl) code

**How to reach me?**

- 📫 k33yb0rd@gmail.com
- :earth_asia: https://www.facebook.com/k33ybord/

```acpi
        Scope (INTR)
        {
            Name (_STR, Unicode ("Hi, My name is @k33ybord"))  // _STR: Description String
            If (_OSI ("Winslow"))
            {
                Method (_DSM, 4, NotSerialized)  // _DSM: Device-Specific Method
                {
                    If (!Arg2)
                    {
                        Return (Buffer (22)
                        {
                             0x06                                             // .
                        })
                    }

                    Return (Package (0x83)
                    {
                        "email-me", 
                        X
                    })
                }
            }
        }
```
<!---
k33yb0rd/k33yb0rd is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

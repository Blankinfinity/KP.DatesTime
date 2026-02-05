# KP.DatesTime

A comprehensive C# library providing useful DateTime utility functions and extensions for .NET applications.

## Overview

KP.DatesTime is a .NET class library designed to simplify common DateTime operations and provide additional functionality for date and time manipulation in your applications.

## Features

- **Date/Time Utilities**: Common date and time operations
- **Extensions**: Helpful extension methods for DateTime objects
- **Formatting**: Enhanced date/time formatting options
- **Calculations**: Date arithmetic and business day calculations
- **Parsing**: Robust date/time parsing capabilities

## Requirements

- **.NET Framework**: 4.5.2 or higher
- **Visual Studio**: 2015 or later (recommended)
- **Target Platform**: Any CPU

## Installation

### From Source

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Open the solution in Visual Studio:
   ```
   KP.DatesTime.sln
   ```

3. Build the solution:
   - Press `Ctrl+Shift+B` or
   - Go to **Build** → **Build Solution**

### Binary Distribution

Add the compiled DLL as a reference to your project:

1. Right-click on **References** in your project
2. Select **Add Reference...**
3. Browse to the compiled `KP.DatesTime.dll`
4. Click **OK**

## Usage

```csharp
using KP.DatesTime;

// Example usage will be added as functionality is implemented
// DateTime now = DateTime.Now;
// var result = now.SomeExtensionMethod();
```

## Project Structure

```
KP.DatesTime/
├── KP.DatesTime.sln          # Visual Studio solution file
├── README.md                 # This file
├── .gitignore               # Git ignore rules
├── .gitattributes           # Git attributes
└── KP.DatesTime/            # Main project directory
    ├── Class1.cs            # Main implementation (to be developed)
    ├── KP.DatesTime.csproj  # Project file
    └── Properties/
        └── AssemblyInfo.cs  # Assembly metadata
```

## Development

### Building the Project

1. **Debug Build**:
   ```bash
   msbuild KP.DatesTime.sln /p:Configuration=Debug
   ```

2. **Release Build**:
   ```bash
   msbuild KP.DatesTime.sln /p:Configuration=Release
   ```

### Adding New Features

1. Implement new DateTime utilities in the main classes
2. Add appropriate unit tests
3. Update documentation
4. Follow C# coding conventions

### Code Style

- Follow standard C# naming conventions
- Use XML documentation comments for public methods
- Maintain compatibility with .NET Framework 4.5.2+

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-datetime-utility`)
3. Commit your changes (`git commit -am 'Add new DateTime utility'`)
4. Push to the branch (`git push origin feature/new-datetime-utility`)
5. Create a Pull Request

## Planned Features

- [ ] Date range operations
- [ ] Business day calculations
- [ ] Time zone utilities
- [ ] Date formatting extensions
- [ ] Relative date calculations
- [ ] Holiday detection
- [ ] Recurring date patterns

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0.0 | 2017 | Initial project structure |

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

**KP (BlankInfinity Projects)**

## Support

For questions, issues, or feature requests, please:

1. Check existing issues in the repository
2. Create a new issue with detailed information
3. Contact the maintainer

---

**Note**: This library is currently in development. The main functionality is yet to be implemented in `Class1.cs`.

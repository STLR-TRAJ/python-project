# Advanced Date & Time Calculator Pro

A comprehensive, secure, and modern desktop application for all kinds of date and time calculations built with Python and CustomTkinter.

## Features

### 🔒 Security Features
- **Input Validation & Sanitization**: All user inputs are validated and sanitized to prevent malicious attacks
- **SQL Injection Protection**: Parameterized queries and input validation for database operations
- **Path Traversal Protection**: Filename sanitization for file operations
- **Data Encryption**: User preferences and sensitive data are encrypted
- **Comprehensive Logging**: All operations are logged for security monitoring

### 🎨 Modern UI Design
- **Dark/Light Themes**: Customizable appearance with system theme detection
- **Responsive Layout**: Scales properly on different screen sizes
- **Modern Components**: Built with CustomTkinter for a modern look
- **Intuitive Navigation**: Easy-to-use sidebar navigation with search functionality
- **Visual Feedback**: Progress indicators and status updates

### 📊 Core Calculations

#### 1. **Duration Calculator**
- Calculate precise time differences between two dates
- Multiple format options (years, months, days, hours, minutes, seconds)
- Working days calculation with weekend/holiday exclusion
- Detailed breakdown with alternative representations

#### 2. **Date Arithmetic**
- Add or subtract time periods from dates
- Support for years, months, weeks, days, hours, minutes, seconds
- Precision time calculations with validation
- Historical context and additional information

#### 3. **Timezone Converter**
- Convert times between multiple timezones
- Support for all major world timezones
- Batch conversion to multiple target zones
- UTC offset calculations and daylight saving time handling

#### 4. **Working Days Calculator**
- Calculate business days excluding weekends
- Holiday support for multiple countries
- Detailed breakdown with percentage analysis
- Custom holiday management

#### 5. **Age Calculator**
- Precise age calculation with detailed breakdown
- Milestone tracking and next birthday countdown
- Alternative representations (days, hours, minutes lived)
- Zodiac sign and seasonal information

#### 6. **Day of Week Finder**
- Find day of week for any date in history or future
- Historical context and relative time calculations
- Calendar information (week of year, day of year, etc.)
- Leap year detection and special date handling

#### 7. **Unix Timestamp Converter**
- Bidirectional conversion between timestamps and dates
- Support for seconds and milliseconds
- Multiple timezone outputs
- Various format representations (decimal, hex, binary)

### 🌙 Advanced Astronomical Features
- **Moon Phase Calculator**: Calculate lunar phases for any date
- **Sunrise/Sunset Calculator**: Precise calculations based on location
- **Seasonal Information**: Automatic season detection
- **Celestial Events**: Integration with astronomical databases

### 📈 Business Calendar Features
- **Holiday Management**: Support for holidays from multiple countries
- **Custom Events**: Add and manage custom recurring events
- **Business Day Analysis**: Comprehensive working day calculations
- **Holiday Impact Analysis**: See how holidays affect business days

### 🔄 Recurring Events
- **Pattern Generation**: Create recurring date patterns
- **Multiple Frequencies**: Daily, weekly, monthly, yearly patterns
- **Custom Intervals**: Every N occurrences support
- **End Date or Count**: Generate until specific date or count

### 📊 Time Analytics & Visualization
- **Usage Analytics**: Track your calculation patterns
- **Visual Charts**: Graphical representation of time data
- **Pattern Recognition**: Identify trends in your calculations
- **Export Charts**: Save visualizations as images

### 💾 Data Management
- **Calculation History**: Persistent storage of all calculations
- **Favorites System**: Save frequently used calculations
- **Search & Filter**: Find specific calculations quickly
- **Import/Export**: Support for JSON, CSV, Excel formats
- **Data Backup**: Secure backup and restore functionality

### ⚙️ Advanced Settings
- **Customizable Preferences**: Extensive configuration options
- **Theme Selection**: Dark, light, or system themes
- **Default Timezone**: Set preferred timezone
- **Date Format**: Multiple date format options
- **Auto-save**: Automatic calculation saving
- **Security Settings**: Configurable security parameters

## Installation

### Prerequisites
- Python 3.8 or higher
- Windows, macOS, or Linux

### Dependencies
The application automatically installs these dependencies:
- `customtkinter` - Modern UI framework
- `tkcalendar` - Date picker widgets
- `pytz` - Timezone support
- `holidays` - Holiday data
- `numpy` - Numerical calculations
- `matplotlib` - Data visualization
- `pandas` - Data manipulation
- `cryptography` - Data encryption
- `ephem` - Astronomical calculations
- `skyfield` - Advanced astronomy
- `dateutil` - Date parsing and manipulation
- `pillow` - Image processing
- `requests` - HTTP requests
- `beautifulsoup4` - HTML parsing

### Setup
1. Clone or download the application files
2. Navigate to the project directory
3. Run the application:
   ```bash
   python advanced_datetime_calculator.py
   ```

The application will automatically create a virtual environment and install all required dependencies on first run.

## Usage

### Getting Started
1. Launch the application
2. Select a calculation type from the sidebar
3. Input your data using the intuitive forms
4. Click calculate to see detailed results
5. All calculations are automatically saved to history

### Navigation
- **Sidebar**: Browse available calculation tools
- **Search**: Find specific tools quickly
- **Dashboard**: Overview of recent activity and statistics
- **History**: Review all past calculations
- **Settings**: Customize application behavior

### Security
- All user inputs are automatically validated
- Data is stored locally with encryption
- No data is transmitted to external servers
- Regular security updates are applied

## File Structure

```
advanced_datetime_calculator.py    # Main application file
advanced_features.py              # Additional advanced features
datetime_calculator.db           # Local database (created automatically)
datetime_calculator.log          # Application logs
README.md                       # This documentation
```

## Database Schema

The application uses SQLite with the following tables:
- `calculations` - Stores all calculation history
- `user_preferences` - User settings and preferences
- `custom_holidays` - User-defined holidays
- `favorites` - Saved favorite calculations

## Security Features

### Input Validation
- Maximum input length limits
- Character allowlist validation
- SQL injection prevention
- Path traversal protection

### Data Protection
- AES encryption for sensitive data
- PBKDF2 key derivation
- Secure random salt generation
- Protected file operations

### Logging
- Comprehensive operation logging
- Error tracking and monitoring
- Security event detection
- Performance monitoring

## Troubleshooting

### Common Issues

**Application won't start:**
- Ensure Python 3.8+ is installed
- Check that all dependencies are installed
- Review the log file for error details

**Calculation errors:**
- Verify input data formats
- Check date ranges are valid
- Ensure timezone names are correct

**Database issues:**
- Delete `datetime_calculator.db` to reset
- Check file permissions
- Verify disk space availability

**Theme issues:**
- Reset theme in Settings
- Restart the application
- Update CustomTkinter library

### Support
Check the application logs in `datetime_calculator.log` for detailed error information.

## Contributing

This application is designed to be extensible. To add new calculation types:

1. Create new page methods in the main class
2. Add navigation buttons in the sidebar
3. Implement calculation logic with proper validation
4. Add database storage for results
5. Include comprehensive error handling

## License

This software is provided as-is for educational and personal use.

## Changelog

### Version 1.0.0
- Initial release with comprehensive date/time calculations
- Modern UI with dark/light themes
- Security features and input validation
- Database storage and history tracking
- Advanced astronomical calculations
- Business calendar features
- Import/export functionality
- Comprehensive documentation

---

**© 2024 Advanced Date & Time Calculator Pro**
*Secure, Advanced, Professional*

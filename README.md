# AADS Live Stream Stats Display

A customizable live stream overlay tool for displaying Dart Connect standings with branded AADS headers and footers.

## 🎯 Features

- **URL Loading**: Load any Dart Connect standings page into a branded display
- **Position Controls**: Fine-tune iframe position with 2px precision
- **Zoom & Resize**: Adjust zoom level and iframe dimensions
- **Color Themes**: 7 pre-built color themes (Gold, Orange, Red, Navy, Teal, Purple, Slate)
- **Text Customization**: Change text colors with presets or custom color picker
- **Group Overlays**: Add custom "Group A" and "Group B" bars over Dart Connect headers
- **Layout Controls**: Adjust header/footer width and positioning
- **Settings Lock**: Freeze all settings during streaming to prevent accidental changes
- **Collapsible Controls**: Hide the control panel for clean OBS capture
- **Persistent Settings**: All settings saved in browser localStorage

## 🚀 Usage

### Live Demo
Access the tool online at: **[https://dowdarts.github.io/aads-stats-display/](https://dowdarts.github.io/aads-stats-display/)**

### Basic Setup
1. Open the tool in your browser
2. Paste a Dart Connect URL in the URL tab
3. Click "Load" to display the standings
4. Adjust position, zoom, and styling using the control tabs
5. Lock settings when ready to stream
6. Hide controls using the toggle button (top-right)

### OBS Setup
1. Add a Browser Source in OBS
2. Set URL to: `https://dowdarts.github.io/aads-stats-display/`
3. Set width/height to match your stream resolution
4. In the tool, configure your layout and lock settings
5. Crop out the control header in OBS (or hide it with the toggle button)
6. The branded header, stats display, and footer will remain visible

### Control Tabs

#### **URL Tab**
- Enter Dart Connect URL
- Load/Clear buttons

#### **Position Tab**
- Move iframe with arrow buttons (2px precision)
- Adjust zoom level (10-500%)
- Set width and height percentages
- Reset button to restore defaults

#### **Style Tab**
- Choose from 7 color themes
- Customize text color (white, black, yellow, or custom)

#### **Layout Tab**
- Adjust header width (600-2000px or full width)
- Move footer up/down
- Edit footer text

#### **Groups Tab**
- Show/hide Group A and Group B overlay bars
- Position overlays to cover Dart Connect headers
- Reset positions

## 🎨 Color Themes
- **Gold** (Default) - Yellow/Gold gradient
- **Orange** - Bright orange gradient
- **Red** - Bold red gradient
- **Navy** - Deep blue gradient
- **Teal** - Cyan/Teal gradient
- **Purple** - Rich purple gradient
- **Slate** - Cool gray gradient

## 💾 Settings Persistence
All settings are automatically saved to browser localStorage:
- URL
- Position, zoom, dimensions
- Color theme and text colors
- Header/footer layout
- Group overlay positions
- Lock and collapse states

## 🔒 Settings Lock
When streaming live, click the **Lock** button to:
- Prevent accidental setting changes
- Disable scrolling
- Gray out controls
- Maintain your configured layout

## 📝 Tips
- Set 2px position increments for precise alignment
- Use Group overlays to rebrand Dart Connect headers with AADS branding
- Lock settings before going live to prevent layout shifts
- Hide controls during streaming for a clean display
- All settings persist between sessions

## 🛠️ Technical Details
- Built with vanilla HTML, CSS, and JavaScript
- Uses Tailwind CSS for styling (CDN)
- No build process required
- Fully client-side (no server needed)
- Settings stored in browser localStorage

## 📄 License
MIT License - Feel free to use and modify for your dart league streaming needs!

---

Created for AADS Dart League live stream broadcasts
# UI Components

This guide explains about the available UI components.

Note: Both the terms **control** and **component** are used to refer to a User Interface (UI) component; and can be used inter-changeably. 

## Dependencies

- Tizen 2.4 or later versions for Mobile
- Tizen 3.0 or later versions for Wearable

UI components are interactive components for layouting and scrolling the user interface. DALi provides UI components, such as buttons, item view, scroll view, table view, text controls, image view, flex container, model3dview, slider, and video view.

**Figure: DALi UI components**

![DALi UI components](./media/ui_controls.png)

![DALi UI components](./media/ui_controls2.png)

The following table lists the available UI components.

**Table: DALi UI components**

| Control                               | Description                              | Related classes                          |
|-------------------------------------|----------------------------------------|----------------------------------------|
| [Buttons](buttons.md)             | A **push button** that can be pressed. A **check box** that can be selected or cleared. A **radio button** where only one option can be selected.| `Button`, `PushButton`, `CheckBoxButton`, `RadioButton` |
| [FlexContainer](flexcontainer.md) | This control is a layout model that allows responsive elements within a container, to automatically arrange the elements to different screen sizes or devices. | `FlexContainer`              |
| [ImageView](imageview.md)         | This control is used to render an image.     | `ImageView`                              |
| [ItemView](itemview.md)           | This control is used to enable render item sets in a scrollable layout. | `ItemView`, `ItemFactory`, `ItemLayout`, `Scrollable` |
| [Model3dView](model3dview.md)     | This control is used to enable static 3D content display capability. | `Model3dView`                            |
| [ProgressBar](./progressbar-n.md) | This control gives you a recursive update on the progress of an ongoing operation. | `ProgressBar` 
| [ScrollView](scrollview.md)       | This control is used to enable the scroll function in the UI. | `ScrollView`, `Scrollable`, `ScrollViewEffect`, `ScrollViewPagePathEffect` |
| [Slider](slider.md)               | This control allows you to select a value within a predefined range. | `Slider`                                 |
| [TableView](tableview.md)         | This control is used to enable render a grid layout of text. | `TableView`                              |
| [TextLabel](textlabel.md)         | This control is used to enable render a short text string. | `TextLabel`                              |
| [TextField](textfield.md)         | This control is used to enable a field for one-line of editable text. | `TextField`                              |
| [TextEditor](texteditor.md)       | This control is used to enable a field for multiple lines of editable text. | `TextEditor`                            |
| [VideoView](videoview.md)         | This control is used to enable video playback. | `VideoView`                              |

The base class for the components is Dali::Toolkit::Control (in [mobile] (http://org.tizen.native.mobile.apireference/classDali_1_1Toolkit_1_1Control.html) and [wearable] (http://org.tizen.native.wearable.apireference/classDali_1_1Toolkit_1_1Control.html) applications). It can also be used to create your own custom UI components. 

For more information control class, see [Control](control-base.md). You can [customize the look of the UI components with stylesheets](styling.md). For a reusable rendering logic that can be used by all UI components, take advantage of [DALi visuals](visuals.md).

The following figure illustrates the hierarchy of the UI components.

**Figure: DALi UI component hierarchy**

![DALi UI component hierarchy](./media/ui_control_hierarchy.png)

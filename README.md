# rect_editor
Simple Hotspot .rect editor for new Hammer++ feature.

https://developer.valvesoftware.com/wiki/Hotspot_texturing

## Keymap:
- LMB drag - draw rectangle (snaps to grid)
- RMB click - delete rectangle under cursor
- MMB drag - pan canvas
- Mouse‑wheel - zoom in/out
- "–" and "+" or  "[" and "]" - halve or double grid (like in Hammer Editor)

## Screenshots and final `.rect` code example:
<img width="969" height="933" alt="изображение" src="https://github.com/user-attachments/assets/1c5c8422-49d4-40ea-a469-aae93b632751" />
<img width="985" height="935" alt="изображение" src="https://github.com/user-attachments/assets/2f243c9c-ba9f-479e-ac9e-d0c53d226cc2" />

```
Rectangles
{
	rectangle
	{
		min		"0 0"
		max		"128 128"
	}
	rectangle
	{
		min		"128 0"
		max		"256 128"
	}
	rectangle
	{
		min		"0 128"
		max		"128 256"
	}
	rectangle
	{
		min		"128 128"
		max		"256 256"
	}
	rectangle
	{
		min		"0 256"
		max		"128 384"
	}
	rectangle
	{
		min		"128 256"
		max		"256 384"
	}
	rectangle
	{
		min		"0 384"
		max		"128 512"
	}
	rectangle
	{
		min		"128 384"
		max		"256 512"
	}
	rectangle
	{
		min		"256 0"
		max		"440 128"
	}
	rectangle
	{
		min		"256 128"
		max		"440 256"
	}
	rectangle
	{
		min		"256 256"
		max		"440 384"
	}
	rectangle
	{
		min		"256 384"
		max		"440 512"
	}
	rectangle
	{
		min		"440 0"
		max		"512 128"
	}
	rectangle
	{
		min		"440 128"
		max		"512 256"
	}
	rectangle
	{
		min		"440 384"
		max		"512 512"
	}
	rectangle
	{
		min		"440 256"
		max		"512 384"
	}
}
```


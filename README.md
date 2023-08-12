# layzyidiot

###### (or lazyidiot on discord)



i do lua stuff

here's a basic print, a loop, a reversed way, an even more strange reverse way, and... just a basic obfuscation *manually* (painstakingly) made to create a 5x5x5 cube 10 studs in the air with text saying "he does lua stuff!".
```lua
print("he does lua stuff!")


local t = {"he", " does", " lua", " stuff!"}
local str = ""

for i=1, #t do
	
	str = str..t[i]	
	
end

print(str)

local t2 = {"seod eh", "ffuts aul "}

print(string.reverse(t2[1])..string.reverse(t2[2]).."!")

print(string.reverse("!"..string.reverse(string.reverse(t2[2]))..string.reverse(string.reverse(t2[1]))))

local p:Part=Instance.new("Part");p.Anchored=true;p.Parent=workspace;local g:SurfaceGui=Instance.new("SurfaceGui");g.Parent=p;local t:TextLabel=Instance.new("TextLabel");t.Parent=g;t.Text=string.reverse("!"..string.reverse(string.reverse(t2[2]))..string.reverse(string.reverse(t2[1])));t.Size=UDim2.new(1,0,1,0);p.Size=Vector3.new(5,5,5);p.Position=Vector3.new(0,10,0);t.TextScaled=true;t.BackgroundTransparency=1
```

### *so, uhh... what brings you to my profile?*

--[[
  Made By Z_lqify
    CARPECT
--]]
local PluginManagerObject = PluginManager()
local Plugin = PluginManagerObject:CreatePlugin()
local Toolbar = Plugin:CreateToolbar("Carpect")
local Button = Toolbar:CreateButton("", "Create Tween", "")



if game.ReplicatedStorage:FindFirstChild("CARPECTSRC") == nil then
	local Folder = Instance.new("Folder")
	Folder.Name = "CARPECTSRC"
	Folder.Parent = game.ReplicatedStorage
end


local Displays = {
	["Position"] = {"Vector3.new(",")"},
	["CFrame"] = {"CFrame.new(",")"},
}

local BlockedProperties = {
	"DataCost",
}
local ReadOnly = {
	"ClassName",
}

local oldProperties = {}
Derived = {
	Instance = { "Name", "Parent", "Archivable", "ClassName", "RobloxLocked", "DataCost", Derived = {
		Accoutrement = { "AttachmentForward", "AttachmentRight", "AttachmentPoint", "AttachmentPos", "AttachmentUp", "BackendAccoutrementState", Derived = {
			Hat = { Derived = {} }
		}},
		Animation = { "AnimationId", Derived = { } },
		AnimationTrack = { Derived = { } },
		Backpack = { Derived = { } },
		BaseScript = { "Disabled", "LinkedSource", Derived = {
			CoreScript = { Derived = { } },
			Script = { "Source", "Disabled", Derived = { 
				LocalScript = { Derived = { } }
			}}
		}},
		BodyAngularVelocity = { "angularvelocity", "P", "maxTorque", Derived = { } },
		BodyColors = { "BodyColor", Derived = { } },
		BodyForce = { "force", Derived = { } },
		BodyGyro = { "D", "P", "cframe", "maxTorque", Derived = { } },
		BodyPosition = { "D", "P", "maxForce", "position", Derived = { } },
		BodyThrust = { "force", "location", Derived = { } },
		BodyVelocity = { "P", "maxForce", "Velocity", Derived = { } },
		BoolValue = { "Value", Derived = { } },
		BrickColorValue = { "Value", Derived = { } },
		Camera = { "CameraSubject", "CameraType", "CoordinateFrame", "Focus", Derived = { } },
		CFrameValue = { "Value", Derived = { } },
		ClickDetector = { "MaxActivationDistance", Derived = { } },
		Clothing = { Derived = {
			Pants = { "PantsTemplate", Derived = { } },
			Shirt = { "ShirtTemplate", Derived = { } }
		}},
		Color3Value = { "Value", Derived = { } },
		Configuration = { Derived = { } },
		Dialog = { "ConversationDistance", "InUse", "InitailPrompt", "Purpose", "Tone", Derived = { } },
		DialogChoice = { "ResponseDialog", "UserDialog", Derived = { } },
		Explosion = { "BlastPressure", "BlastRadius", "Position", Derived = { } },
		Feature = { "FaceId", "InOut", "LeftRight", "TopBottom", Derived = {
			Hole = { Derived = { } },
			MotorFeature = { Derived = { } }
		}},
		Fire = { "Color", "Enabled", "Heat", "SecondaryColor", "Size", Derived = { } },
		ForceField = { Derived = { } },
		GuiBase = { "AbsolutePosition", "AbsoluteSize", Derived = {
			ScreenGui = { Derived = { } },
			GuiObject = { "Active", "BackgroundColor3", "BackgroundTransparency", "BorderColor3", "BorderSizePixel", "Position", "Size", "SizeConstraint", "Visible", "ZIndex", Derived = {
				Frame = { Derived = { } },
				GuiButton = { "AutoButtonColor", "Selected", "Style", Derived = {
					ImageButton = { "Image", Derived = { } },
					TextButton = { "Text", "TextBounds", "TextWrap", "TextColor3", "TextTransparency, TextXAlignment", "TextYAlignment", "FontSize", "Font", Derived = { } }
				}},
				GuiLabel = { Derived = {
					ImageLabel = { "Image", Derived = { } },
					TextLabel = { "Text", "TextBounds", "TextWrap", "TextColor3", "TextTransparency, TextXAlignment", "TextYAlignment", "FontSize", "Font", Derived = { } }
				}},
				TextBox = { "Text", "TextBounds", "TextWrap", "TextColor3", "TextTransparency, TextXAlignment", "TextYAlignment", "FontSize", "Font", Derived = { } }
			}},
			BillboardGui = { "Adornee", "Enabled", "ExtentsOffset", "SizeOffset", "StudsOffset", Derived = { } },
		}},
		GuiBase3d = { "Color", "Transparency", "Visible", Derived = {
			PartAdornment = { "Adornee", Derived = {
				SurfaceSelection = { "TargetSurface", Derived = { } },
			}},
			PVAdornment = { "Adornee", Derived = {
				SelectionBox = { Derived = { } }
			}},
			SelectionLasso = { "Humanoid", Derived = {
				SelectionPartLasso = { "Part", Derived = { } },
				SelectionPointLasso = { "Point", Derived = { } },
			}}
		}},
		Humanoid = { "Health", "Jump", "MaxHealth", "PlatformStand", "RightLeg", "Sit", "TargetPoint", "Torso", "WalkDirection", "WalkSpeed", "WalkToPart", "WalkToPoint", Derived = { } },
		IntValue = { "Value", Derived = { } },
		JointInstance = { "C0", "C1", "Part0", "Part1", Derived = {
			DynamicRotate = { "BaseAngle", Derived = {
				RotateP = { Derived = { } },
				RotateV = { Derived = { } }
			}},
			Glue = { "F0", "F1", "F2", "F3", Derived = { } },
			Motor = { "CurrentAngle", "DesiredAngle", "MaxVelocity", Derived = { } },
			Rotate = { Derived = { } },
			Snap = { Derived = { } },
			VelocityMotor = { "CurrentAngle", "DesiredAngle", "Hole", "MaxVelocity", Derived = { } },
			Weld = { Derived = { } }
		}},
		KeyFrame = { "Time", Derived = { } },
		Message = { "Text", Derived = {
			Hint = { Derived = { } },
		}},
		Mouse = { "Hit", "Icon", "Origin", "Target", "TargetFilter", "TargetSurface", "UnitRay", "ViewSizeX", "ViewSizeY", "X", "Y", Derived = { } },
		NetworkReplicator = { "Port", Derived = { } },
		NumberValue = { "Value", Derived = { } },
		ObjectValue = { "Value", Derived = { } },
		Player = { "AccountAge", "Character", "CharacterAppearance", "DataReady", "Neutral", "MembershipType", "TeamColor", "userId",  Derived = { } },
		Pose = { "CFrame", "MaskWeight", "Weight", Derived = { } },
		PVInstance = { Derived = {
			BasePart = { "Anchored", "Color", "CFrame", "CanCollide", "Elasticity", "Friction", "Locked", "Material", "Position", "Reflectance", "RotVelocity", "Size", "Transparency", "Velocity", "TopParamA", "BottomParamA", "LeftParamA", "RightParamA", "FrontParamA", "BackParamA", "TopParamB", "BottomParamB", "LeftParamB", "RightParamB", "FrontParamB", "BackParamB", "TopSurface", "BottomSurface", "LeftSurface", "RightSurface", "FrontSurface", "BackSurface", "TopSurfaceInput", "BottomSurfaceInput", "LeftSurfaceInput", "RightSurfaceInput", "FrontSurfaceInput", "BackSurfaceInput", Derived = {
				CornerWedgePart = { Derived = { } },
				FormFactorPart = { "FormFactor", Derived = {
					FlagStand = { "TeamColor", Derived = { } },
					Part = { "Shape", Derived = {
						Seat = { Derived = { } },
						SpawnLocation = { "AllowTeamChangeOnTouch", "Duration", "Neutral", "TeamColor", Derived = { } }
					}},
					WedgePart = { Derived = { } },
				}},
				ParallelRampPart = { Derived = { } },
				PrismPart = { "Sides", Derived = { } },
				PyramidPart = { "Sides", Derived = { } },
				RightAngleRampPart = { Derived = { } },
				SkateboardPlatform = { "Controller", "ControllingHumanoid", "Steer", "StickyWheels", "Throttle", Derived = { } },
				TrussPart = { "Style", Derived = { } },
				VehicleSeat = { "AreHingesDetected", "HeadsUpDisplay", "MaxSpeed", "Steer", "Throttle", "Torque", "TurnSpeed", Derived = { } }
			}},
			Model = { "PrimaryPart", Derived = { } }
		}},
		RayValue = { "Value", Derived = { } },
		RocketPropulsion = { "TurnP", "TurnD", "ThrustP", "ThrustD", "TargetRadius", "TargetOffset", "Target", "MaxTorque", "MaxThrust", "MaxSpeed", "CartoonFactor", Derived = { } },
		ScriptContext = { "GarbageCollectionFrequency", "GarbageCollectionLimit", "ScriptsDisabled", Derived = { } },
		ShirtGraphic = { "Graphic", Derived = { } },
		Skin = { "SkinColor", Derived = { } },
		Sky = { "CelestialBodiesShown", "SkyboxBk", "SkyboxDn", "SkyboxFt", "SkyboxRt", "SkyboxUp", "SkyboxCount", Derived = { } },
		Smoke = { "Color", "Enabled", "Opacity", "RiseVelocity", "Size", Derived = { } },
		Sound = { "IsPaused", "IsPlaying", "Looped", "Pitch", "PlayOnRemove", "SoundId", "Volume", Derived = { } },
		Sparkles = { "Enabled", "SparkleColor", Derived = { } },
		StarterGear = { Derived = { } },
		StatsItem = { Derived = {
			ProfilingItem = { Derived = { } },
		},
		StringValue = { "Value", Derived = { } },
		Team = { "AutoAssignable", "AutoColorCharacters", "Score", "TeamColor", Derived = { } },
		Teams = { Derived = { } },
		TouchTransmitter = { "Target", Derived = { } },
		Vector3Value = { "Value", Derived = { } }
		}}}}

function AddToTable(a, b)
	local r = { }
	for i,v in next, a do
		if type(v) == "string" then
			r[#r+1] = v
		end
	end
	for i,v in next, b do
		if type(v) == "string" then
			r[#r+1] = v
		end
	end
	return r
end

function Properties(obj, fenv)
	fenv = fenv or getfenv()
	for i,v in next, fenv.Derived do
		if obj:IsA(i) then
			return AddToTable(v, Properties(obj, v) or { })
		end
	end
end

function GetProperties(obj)
	local tab = Properties(obj)
	for i,v in next, tab do
		if type(v) == "table" then
			table.remove(tab, i)
		end
	end
	return tab
end
local clone = nil
local cloneind = nil
local Selection = game:GetService("Selection")
local object
local isOn = false
local UI = game.InsertService:LoadAsset("10066922931").UI
UI.Parent = game:GetService("CoreGui")
UI.Enabled = false
local getSelected 
local output = nil
local TweenService = 'game:GetService("TweenService")'
local DefaultAnimationLength = 1
local AnimationLength = nil
local propertieschanged = {}

Button.Click:Connect(function()
	print(isOn)
	if isOn == false then
		UI.Enabled = true
		isOn = true
		if UI.Main.Visible == true then
			local selected = false
			while true do
				wait(0.001)
				getSelected = Selection:Get()
				if #getSelected == 1 then
					getSelected = getSelected[1]
					if UI.Main.Reset.Visible == false then
						UI.Main.Next1.Visible = true
						selected = true
					end
				else
					UI.Main.Next1.Visible = false
					selected = false
				end
			end
		end
	else
		isOn = false
		UI.Enabled = false
	end
end)

local main = UI.Main
main.close.MouseButton1Up:Connect(function()
	UI.Enabled = false
	isOn = false
end)
main.Next1.MouseButton1Up:Connect(function()
	main.Next1.Visible = false
	main.Next2.Visible = true
	main.T1.Visible = false
	main.T2.Visible = true
	local gotProperties = GetProperties(getSelected)
	if gotProperties == nil then return end
	object = getSelected
	for index,property in pairs(gotProperties) do
		for _,v in pairs(BlockedProperties) do
			if property ~= v then
				oldProperties[property] = object[property]
			end
		end
	end
	print(oldProperties)
end)

main.Next2.MouseButton1Up:Connect(function()
	local properties = GetProperties(getSelected)
	propertieschanged = {}
	for _,v in pairs(GetProperties(getSelected)) do
		for _,val in pairs(BlockedProperties) do
			if val ~= v then
				if oldProperties[v] ~= object[v] then
					propertieschanged[v] = object[v]
				end
			end
		end
	end
	clone = object:Clone()
	cloneind = #game.ReplicatedStorage:WaitForChild("CARPECTSRC"):GetChildren()
	clone.Name = "CARPECTCLN" .. cloneind
	clone.Parent = game.ReplicatedStorage:WaitForChild("CARPECTSRC")
	clone:ClearAllChildren()
	print(propertieschanged)
	main.Done1.Visible = true
	main.T3.Visible = true
	main.Next2.Visible = false
	main.T2.Visible = false
	main.AnimationLength.Visible = true
	for i,v in pairs(oldProperties) do
		for _,val in pairs(ReadOnly) do
			if val ~= i then
				object[i] = v
			end
		end
		
	end
end)

main.Done1.MouseButton1Up:Connect(function()
	AnimationLength = tonumber(main.AnimationLength.Text)
	if AnimationLength == nil then
		AnimationLength = DefaultAnimationLength
	end
	local getParent = {}
	getParent = {object}
	while true do
		getParent[#getParent + 1] = getParent[#getParent].Parent
		if getParent[#getParent] == game then
			break
		end
	end
	for i = 1, math.floor(#getParent/2) do
		local j = #getParent - i + 1
		getParent[i], getParent[j] = getParent[j], getParent[i]
	end
	getParent[1] = "game"
	for i,v in pairs(getParent) do
		if i > 1 then
			getParent[i] = tostring(v)
		end
	end
	local getGoal = {}
	for i,v in pairs(propertieschanged) do
		getGoal[#getGoal + 1] = tostring(tostring(i) .. " = " .. "game.ReplicatedStorage.CARPECTSRC.".. "CARPECTCLN" .. cloneind .. "." .. tostring(i))
	end
	print(getParent)
	print(getGoal)
	output = TweenService .. ":Create(" .. table.concat(getParent,".") ..", TweenInfo.new(" .. AnimationLength .. "), {" .. table.concat(getGoal, ", ") .. "}):Play()"
	main.Reset.Visible = true
	main.T4.Visible = true
	main["T4.1"].Visible = true
	main.codeoutput.Visible = true
	main.codeoutput.Text = output
	main.Done1.Visible = false
	main.T3.Visible = false
	main.Next2.Visible = false
	main.Next1.Visible = false
	main.T2.Visible = false
	main.AnimationLength.Visible = false
end)

main.Reset.MouseButton1Up:Connect(function()
	main.Reset.Visible = false
	main.T4.Visible = false
	main["T4.1"].Visible = false
	main.codeoutput.Visible = false
	main.T1.Visible = true
	clone = nil
	cloneind = nil
	object = nil
	getSelected = nil
	output = nil
	AnimationLength = nil
	propertieschanged = {}
	oldProperties = {}
end)

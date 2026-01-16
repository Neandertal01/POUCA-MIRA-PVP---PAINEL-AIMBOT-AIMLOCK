
local G2L = {};

-- StarterGui.Painel do Mano
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["Enabled"] = false;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["Name"] = [[Painel do Mano]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.Painel do Mano.Menu
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Size"] = UDim2.new(0, 755, 0, 431);
G2L["2"]["Position"] = UDim2.new(0.17649, 0, 0.33261, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Menu]];


-- StarterGui.Painel do Mano.Menu.Drag
G2L["3"] = Instance.new("LocalScript", G2L["2"]);
G2L["3"]["Name"] = [[Drag]];


-- StarterGui.Painel do Mano.Menu.UICorner
G2L["4"] = Instance.new("UICorner", G2L["2"]);



-- StarterGui.Painel do Mano.Menu.Title 2
G2L["5"] = Instance.new("TextLabel", G2L["2"]);
G2L["5"]["TextWrapped"] = true;
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["TextSize"] = 14;
G2L["5"]["TextScaled"] = true;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(53, 239, 255);
G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["5"]["TextColor3"] = Color3.fromRGB(49, 192, 199);
G2L["5"]["BackgroundTransparency"] = 1;
G2L["5"]["Size"] = UDim2.new(0, 173, 0, 34);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Text"] = [[Melhor Menu para PVP]];
G2L["5"]["Name"] = [[Title 2]];
G2L["5"]["Position"] = UDim2.new(0, 0, 0.0348, 0);


-- StarterGui.Painel do Mano.Menu.Title
G2L["6"] = Instance.new("TextLabel", G2L["2"]);
G2L["6"]["TextWrapped"] = true;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["TextSize"] = 14;
G2L["6"]["TextScaled"] = true;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Size"] = UDim2.new(0, 173, 0, 34);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Text"] = [[POUCA MIRA]];
G2L["6"]["Name"] = [[Title]];


-- StarterGui.Painel do Mano.Menu.Buttons
G2L["7"] = Instance.new("Frame", G2L["2"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["7"]["Size"] = UDim2.new(0, 755, 0, 42);
G2L["7"]["Position"] = UDim2.new(0, 0, 0.11369, 0);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Name"] = [[Buttons]];


-- StarterGui.Painel do Mano.Menu.Buttons.Aim
G2L["8"] = Instance.new("TextButton", G2L["7"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["TextSize"] = 14;
G2L["8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["8"]["Size"] = UDim2.new(0, 92, 0, 32);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Text"] = [[Aimbot/Aimlock]];
G2L["8"]["Name"] = [[Aim]];
G2L["8"]["Position"] = UDim2.new(0.09007, 0, 0.11861, 0);


-- StarterGui.Painel do Mano.Menu.Buttons.Aim.LocalScript
G2L["9"] = Instance.new("LocalScript", G2L["8"]);



-- StarterGui.Painel do Mano.Menu.Buttons.Aim.UICorner
G2L["a"] = Instance.new("UICorner", G2L["8"]);



-- StarterGui.Painel do Mano.Menu.Buttons.Aim.LocalScript
G2L["b"] = Instance.new("LocalScript", G2L["8"]);



-- StarterGui.Painel do Mano.Menu.Buttons.Visual
G2L["c"] = Instance.new("TextButton", G2L["7"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextSize"] = 14;
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c"]["Size"] = UDim2.new(0, 92, 0, 32);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Text"] = [[ESP/VISUAL]];
G2L["c"]["Name"] = [[Visual]];
G2L["c"]["Position"] = UDim2.new(0.32848, 0, 0.11861, 0);


-- StarterGui.Painel do Mano.Menu.Buttons.Visual.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.Painel do Mano.Menu.Buttons.Visual.UICorner
G2L["e"] = Instance.new("UICorner", G2L["c"]);



-- StarterGui.Painel do Mano.Menu.Buttons.Visual.LocalScript
G2L["f"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.Painel do Mano.Menu.Buttons.FPS
G2L["10"] = Instance.new("TextButton", G2L["7"]);
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["TextSize"] = 14;
G2L["10"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["10"]["Size"] = UDim2.new(0, 92, 0, 32);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Text"] = [[DESEMPENHO]];
G2L["10"]["Name"] = [[FPS]];
G2L["10"]["Position"] = UDim2.new(0.54967, 0, 0.11861, 0);


-- StarterGui.Painel do Mano.Menu.Buttons.FPS.LocalScript
G2L["11"] = Instance.new("LocalScript", G2L["10"]);



-- StarterGui.Painel do Mano.Menu.Buttons.FPS.UICorner
G2L["12"] = Instance.new("UICorner", G2L["10"]);



-- StarterGui.Painel do Mano.Menu.Buttons.FPS.LocalScript
G2L["13"] = Instance.new("LocalScript", G2L["10"]);



-- StarterGui.Painel do Mano.Menu.Buttons.Outros
G2L["14"] = Instance.new("TextButton", G2L["7"]);
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["TextSize"] = 14;
G2L["14"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["14"]["Size"] = UDim2.new(0, 92, 0, 32);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Text"] = [[INICIO]];
G2L["14"]["Name"] = [[Outros]];
G2L["14"]["Position"] = UDim2.new(0.78808, 0, 0.11861, 0);


-- StarterGui.Painel do Mano.Menu.Buttons.Outros.LocalScript
G2L["15"] = Instance.new("LocalScript", G2L["14"]);



-- StarterGui.Painel do Mano.Menu.Buttons.Outros.UICorner
G2L["16"] = Instance.new("UICorner", G2L["14"]);



-- StarterGui.Painel do Mano.Menu.Buttons.Outros.LocalScript
G2L["17"] = Instance.new("LocalScript", G2L["14"]);



-- StarterGui.Painel do Mano.Menu.AimFrame
G2L["18"] = Instance.new("Frame", G2L["2"]);
G2L["18"]["Visible"] = false;
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["Size"] = UDim2.new(0, 755, 0, 340);
G2L["18"]["Position"] = UDim2.new(0, 0, 0.21114, 0);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["Name"] = [[AimFrame]];
G2L["18"]["BackgroundTransparency"] = 1;


-- StarterGui.Painel do Mano.Menu.AimFrame.aimbut
G2L["19"] = Instance.new("TextButton", G2L["18"]);
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["19"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[]];
G2L["19"]["Name"] = [[aimbut]];
G2L["19"]["Position"] = UDim2.new(0.01589, 0, 0.03957, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.aimbut.LocalScript
G2L["1a"] = Instance.new("LocalScript", G2L["19"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.aimbut.UICorner
G2L["1b"] = Instance.new("UICorner", G2L["19"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.aimbut.TextLabel
G2L["1c"] = Instance.new("TextLabel", G2L["19"]);
G2L["1c"]["TextWrapped"] = true;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextSize"] = 14;
G2L["1c"]["TextScaled"] = true;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Size"] = UDim2.new(0, 159, 0, 29);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[Ativar Aimbot]];
G2L["1c"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.aimbut.TextLabel.LocalScript
G2L["1d"] = Instance.new("LocalScript", G2L["1c"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.aimlock
G2L["1e"] = Instance.new("TextButton", G2L["18"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextSize"] = 14;
G2L["1e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[]];
G2L["1e"]["Name"] = [[aimlock]];
G2L["1e"]["Position"] = UDim2.new(0.01589, 0, 0.19545, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.aimlock.LocalScript
G2L["1f"] = Instance.new("LocalScript", G2L["1e"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.aimlock.UICorner
G2L["20"] = Instance.new("UICorner", G2L["1e"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.aimlock.TextLabel
G2L["21"] = Instance.new("TextLabel", G2L["1e"]);
G2L["21"]["TextWrapped"] = true;
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["TextSize"] = 14;
G2L["21"]["TextScaled"] = true;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["21"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["BackgroundTransparency"] = 1;
G2L["21"]["Size"] = UDim2.new(0, 159, 0, 29);
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Text"] = [[Ativar AimLock]];
G2L["21"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.aimlock.TextLabel.LocalScript
G2L["22"] = Instance.new("LocalScript", G2L["21"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.auxilio
G2L["23"] = Instance.new("TextButton", G2L["18"]);
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["TextSize"] = 14;
G2L["23"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["23"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["23"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["Text"] = [[]];
G2L["23"]["Name"] = [[auxilio]];
G2L["23"]["Position"] = UDim2.new(0.01589, 0, 0.35721, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.auxilio.LocalScript
G2L["24"] = Instance.new("LocalScript", G2L["23"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.auxilio.UICorner
G2L["25"] = Instance.new("UICorner", G2L["23"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.auxilio.TextLabel
G2L["26"] = Instance.new("TextLabel", G2L["23"]);
G2L["26"]["TextWrapped"] = true;
G2L["26"]["BorderSizePixel"] = 0;
G2L["26"]["TextSize"] = 14;
G2L["26"]["TextScaled"] = true;
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["26"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["26"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["26"]["BackgroundTransparency"] = 1;
G2L["26"]["Size"] = UDim2.new(0, 207, 0, 29);
G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["Text"] = [[Ativar AimAssist]];
G2L["26"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.auxilio.TextLabel.LocalScript
G2L["27"] = Instance.new("LocalScript", G2L["26"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel
G2L["28"] = Instance.new("TextLabel", G2L["18"]);
G2L["28"]["TextWrapped"] = true;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextScaled"] = true;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["28"]["TextColor3"] = Color3.fromRGB(49, 192, 199);
G2L["28"]["BackgroundTransparency"] = 1;
G2L["28"]["Size"] = UDim2.new(0, 352, 0, 45);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[-=======- AIMBOT CONFIG -=======-]];
G2L["28"]["Position"] = UDim2.new(0.47947, 0, 0.01418, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.Force
G2L["29"] = Instance.new("TextBox", G2L["18"]);
G2L["29"]["Name"] = [[Force]];
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["TextWrapped"] = true;
G2L["29"]["TextSize"] = 14;
G2L["29"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["TextScaled"] = true;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["29"]["PlaceholderText"] = [[0.87]];
G2L["29"]["Size"] = UDim2.new(0, 163, 0, 22);
G2L["29"]["Position"] = UDim2.new(0.60397, 0, 0.21507, 0);
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Text"] = [[]];


-- StarterGui.Painel do Mano.Menu.AimFrame.Force.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["29"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel
G2L["2b"] = Instance.new("TextLabel", G2L["18"]);
G2L["2b"]["TextWrapped"] = true;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["TextSize"] = 14;
G2L["2b"]["TextScaled"] = true;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["BackgroundTransparency"] = 1;
G2L["2b"]["Size"] = UDim2.new(0, 89, 0, 28);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Text"] = [[Força]];
G2L["2b"]["Position"] = UDim2.new(0.65298, 0, 0.13183, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel.LocalScript
G2L["2c"] = Instance.new("LocalScript", G2L["2b"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.Range
G2L["2d"] = Instance.new("TextBox", G2L["18"]);
G2L["2d"]["Name"] = [[Range]];
G2L["2d"]["BorderSizePixel"] = 0;
G2L["2d"]["TextWrapped"] = true;
G2L["2d"]["TextSize"] = 14;
G2L["2d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2d"]["TextScaled"] = true;
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2d"]["PlaceholderText"] = [[150]];
G2L["2d"]["Size"] = UDim2.new(0, 163, 0, 22);
G2L["2d"]["Position"] = UDim2.new(0.60397, 0, 0.37684, 0);
G2L["2d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2d"]["Text"] = [[]];


-- StarterGui.Painel do Mano.Menu.AimFrame.Range.UICorner
G2L["2e"] = Instance.new("UICorner", G2L["2d"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel
G2L["2f"] = Instance.new("TextLabel", G2L["18"]);
G2L["2f"]["TextWrapped"] = true;
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["TextSize"] = 14;
G2L["2f"]["TextScaled"] = true;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["BackgroundTransparency"] = 1;
G2L["2f"]["Size"] = UDim2.new(0, 89, 0, 28);
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["Text"] = [[Raio]];
G2L["2f"]["Position"] = UDim2.new(0.65298, 0, 0.29359, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel.LocalScript
G2L["30"] = Instance.new("LocalScript", G2L["2f"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.Distance
G2L["31"] = Instance.new("TextBox", G2L["18"]);
G2L["31"]["Name"] = [[Distance]];
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["TextWrapped"] = true;
G2L["31"]["TextSize"] = 14;
G2L["31"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["TextScaled"] = true;
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["31"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["31"]["PlaceholderText"] = [[300]];
G2L["31"]["Size"] = UDim2.new(0, 163, 0, 22);
G2L["31"]["Position"] = UDim2.new(0.60397, 0, 0.5239, 0);
G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["Text"] = [[]];


-- StarterGui.Painel do Mano.Menu.AimFrame.Distance.UICorner
G2L["32"] = Instance.new("UICorner", G2L["31"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel
G2L["33"] = Instance.new("TextLabel", G2L["18"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["TextSize"] = 14;
G2L["33"]["TextScaled"] = true;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["33"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["BackgroundTransparency"] = 1;
G2L["33"]["Size"] = UDim2.new(0, 89, 0, 28);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["Text"] = [[FOV]];
G2L["33"]["Position"] = UDim2.new(0.65298, 0, 0.44065, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel.LocalScript
G2L["34"] = Instance.new("LocalScript", G2L["33"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.Set
G2L["35"] = Instance.new("TextButton", G2L["18"]);
G2L["35"]["TextWrapped"] = true;
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["TextSize"] = 26;
G2L["35"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["35"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["35"]["Size"] = UDim2.new(0, 218, 0, 29);
G2L["35"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["Text"] = [[Setar Configurações]];
G2L["35"]["Name"] = [[Set]];
G2L["35"]["Position"] = UDim2.new(0.56689, 0, 0.88074, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.Set.UICorner
G2L["36"] = Instance.new("UICorner", G2L["35"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.Set.LocalScript
G2L["37"] = Instance.new("LocalScript", G2L["35"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel
G2L["38"] = Instance.new("TextLabel", G2L["18"]);
G2L["38"]["TextWrapped"] = true;
G2L["38"]["BorderSizePixel"] = 0;
G2L["38"]["TextSize"] = 14;
G2L["38"]["TextScaled"] = true;
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["38"]["TextColor3"] = Color3.fromRGB(49, 192, 199);
G2L["38"]["BackgroundTransparency"] = 1;
G2L["38"]["Size"] = UDim2.new(0, 352, 0, 45);
G2L["38"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["Text"] = [[-=======- AIMLOCK CONFIG -=======-]];
G2L["38"]["Position"] = UDim2.new(0.01589, 0, 0.48771, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.Cabeca
G2L["39"] = Instance.new("TextButton", G2L["18"]);
G2L["39"]["TextWrapped"] = true;
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextSize"] = 26;
G2L["39"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["39"]["Size"] = UDim2.new(0, 199, 0, 23);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Text"] = [[Head]];
G2L["39"]["Name"] = [[Cabeca]];
G2L["39"]["Position"] = UDim2.new(0.11656, 0, 0.7131, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.Cabeca.LocalScript
G2L["3a"] = Instance.new("LocalScript", G2L["39"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.Cabeca.UICorner
G2L["3b"] = Instance.new("UICorner", G2L["39"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.Cabeca.LocalScript
G2L["3c"] = Instance.new("LocalScript", G2L["39"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel
G2L["3d"] = Instance.new("TextLabel", G2L["18"]);
G2L["3d"]["TextWrapped"] = true;
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["TextSize"] = 14;
G2L["3d"]["TextScaled"] = true;
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["3d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["BackgroundTransparency"] = 1;
G2L["3d"]["Size"] = UDim2.new(0, 89, 0, 28);
G2L["3d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["Text"] = [[Lock in]];
G2L["3d"]["Position"] = UDim2.new(0.1894, 0, 0.58771, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel.LocalScript
G2L["3e"] = Instance.new("LocalScript", G2L["3d"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.Corpo
G2L["3f"] = Instance.new("TextButton", G2L["18"]);
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextSize"] = 26;
G2L["3f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["Size"] = UDim2.new(0, 199, 0, 23);
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Text"] = [[Torso]];
G2L["3f"]["Name"] = [[Corpo]];
G2L["3f"]["Position"] = UDim2.new(0.11656, 0, 0.81604, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.Corpo.LocalScript
G2L["40"] = Instance.new("LocalScript", G2L["3f"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.Corpo.UICorner
G2L["41"] = Instance.new("UICorner", G2L["3f"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.Corpo.LocalScript
G2L["42"] = Instance.new("LocalScript", G2L["3f"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.NPC
G2L["43"] = Instance.new("TextButton", G2L["18"]);
G2L["43"]["TextWrapped"] = true;
G2L["43"]["BorderSizePixel"] = 0;
G2L["43"]["TextSize"] = 26;
G2L["43"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["43"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["43"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["43"]["Size"] = UDim2.new(0, 163, 0, 29);
G2L["43"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["43"]["Text"] = [[NPC:OFF]];
G2L["43"]["Name"] = [[NPC]];
G2L["43"]["Position"] = UDim2.new(0.60397, 0, 0.64545, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.NPC.UICorner
G2L["44"] = Instance.new("UICorner", G2L["43"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.NPC.LocalScript
G2L["45"] = Instance.new("LocalScript", G2L["43"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.TC
G2L["46"] = Instance.new("TextButton", G2L["18"]);
G2L["46"]["TextWrapped"] = true;
G2L["46"]["BorderSizePixel"] = 0;
G2L["46"]["TextSize"] = 26;
G2L["46"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["46"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["46"]["Size"] = UDim2.new(0, 163, 0, 29);
G2L["46"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["Text"] = [[Team Check]];
G2L["46"]["Name"] = [[TC]];
G2L["46"]["Position"] = UDim2.new(0.60397, 0, 0.75721, 0);


-- StarterGui.Painel do Mano.Menu.AimFrame.TC.UICorner
G2L["47"] = Instance.new("UICorner", G2L["46"]);



-- StarterGui.Painel do Mano.Menu.AimFrame.TC.LocalScript
G2L["48"] = Instance.new("LocalScript", G2L["46"]);



-- StarterGui.Painel do Mano.Menu.Visuais
G2L["49"] = Instance.new("Frame", G2L["2"]);
G2L["49"]["Visible"] = false;
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["49"]["Size"] = UDim2.new(0, 755, 0, 340);
G2L["49"]["Position"] = UDim2.new(0, 0, 0.21114, 0);
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Name"] = [[Visuais]];
G2L["49"]["BackgroundTransparency"] = 1;


-- StarterGui.Painel do Mano.Menu.Visuais.esp
G2L["4a"] = Instance.new("TextButton", G2L["49"]);
G2L["4a"]["BorderSizePixel"] = 0;
G2L["4a"]["TextSize"] = 14;
G2L["4a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4a"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["4a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4a"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["4a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4a"]["Text"] = [[]];
G2L["4a"]["Name"] = [[esp]];
G2L["4a"]["Position"] = UDim2.new(0.01457, 0, 0.03918, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.esp.LocalScript
G2L["4b"] = Instance.new("LocalScript", G2L["4a"]);



-- StarterGui.Painel do Mano.Menu.Visuais.esp.UICorner
G2L["4c"] = Instance.new("UICorner", G2L["4a"]);



-- StarterGui.Painel do Mano.Menu.Visuais.esp.TextLabel
G2L["4d"] = Instance.new("TextLabel", G2L["4a"]);
G2L["4d"]["TextWrapped"] = true;
G2L["4d"]["BorderSizePixel"] = 0;
G2L["4d"]["TextSize"] = 14;
G2L["4d"]["TextScaled"] = true;
G2L["4d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["4d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["BackgroundTransparency"] = 1;
G2L["4d"]["Size"] = UDim2.new(0, 135, 0, 29);
G2L["4d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4d"]["Text"] = [[Ativar ESP]];
G2L["4d"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.esp.TextLabel.LocalScript
G2L["4e"] = Instance.new("LocalScript", G2L["4d"]);



-- StarterGui.Painel do Mano.Menu.Visuais.t esp
G2L["4f"] = Instance.new("TextButton", G2L["49"]);
G2L["4f"]["BorderSizePixel"] = 0;
G2L["4f"]["TextSize"] = 14;
G2L["4f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4f"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["4f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4f"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["4f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4f"]["Text"] = [[]];
G2L["4f"]["Name"] = [[t esp]];
G2L["4f"]["Position"] = UDim2.new(0.01457, 0, 0.20682, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.t esp.LocalScript
G2L["50"] = Instance.new("LocalScript", G2L["4f"]);



-- StarterGui.Painel do Mano.Menu.Visuais.t esp.UICorner
G2L["51"] = Instance.new("UICorner", G2L["4f"]);



-- StarterGui.Painel do Mano.Menu.Visuais.t esp.TextLabel
G2L["52"] = Instance.new("TextLabel", G2L["4f"]);
G2L["52"]["TextWrapped"] = true;
G2L["52"]["BorderSizePixel"] = 0;
G2L["52"]["TextSize"] = 14;
G2L["52"]["TextScaled"] = true;
G2L["52"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["52"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["52"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["52"]["BackgroundTransparency"] = 1;
G2L["52"]["Size"] = UDim2.new(0, 165, 0, 29);
G2L["52"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["52"]["Text"] = [[Ativar Team ESP]];
G2L["52"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.t esp.TextLabel.LocalScript
G2L["53"] = Instance.new("LocalScript", G2L["52"]);



-- StarterGui.Painel do Mano.Menu.Visuais.l esp
G2L["54"] = Instance.new("TextButton", G2L["49"]);
G2L["54"]["BorderSizePixel"] = 0;
G2L["54"]["TextSize"] = 14;
G2L["54"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["54"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["54"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["54"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["Text"] = [[]];
G2L["54"]["Name"] = [[l esp]];
G2L["54"]["Position"] = UDim2.new(0.01457, 0, 0.38035, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.l esp.LocalScript
G2L["55"] = Instance.new("LocalScript", G2L["54"]);



-- StarterGui.Painel do Mano.Menu.Visuais.l esp.UICorner
G2L["56"] = Instance.new("UICorner", G2L["54"]);



-- StarterGui.Painel do Mano.Menu.Visuais.l esp.TextLabel
G2L["57"] = Instance.new("TextLabel", G2L["54"]);
G2L["57"]["TextWrapped"] = true;
G2L["57"]["BorderSizePixel"] = 0;
G2L["57"]["TextSize"] = 14;
G2L["57"]["TextScaled"] = true;
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["57"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["BackgroundTransparency"] = 1;
G2L["57"]["Size"] = UDim2.new(0, 133, 0, 29);
G2L["57"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["57"]["Text"] = [[Linhas ESP]];
G2L["57"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.l esp.TextLabel.LocalScript
G2L["58"] = Instance.new("LocalScript", G2L["57"]);



-- StarterGui.Painel do Mano.Menu.Visuais.m esp
G2L["59"] = Instance.new("TextButton", G2L["49"]);
G2L["59"]["BorderSizePixel"] = 0;
G2L["59"]["TextSize"] = 14;
G2L["59"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["59"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["59"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["59"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["59"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["59"]["Text"] = [[]];
G2L["59"]["Name"] = [[m esp]];
G2L["59"]["Position"] = UDim2.new(0.01457, 0, 0.56565, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.m esp.LocalScript
G2L["5a"] = Instance.new("LocalScript", G2L["59"]);



-- StarterGui.Painel do Mano.Menu.Visuais.m esp.UICorner
G2L["5b"] = Instance.new("UICorner", G2L["59"]);



-- StarterGui.Painel do Mano.Menu.Visuais.m esp.TextLabel
G2L["5c"] = Instance.new("TextLabel", G2L["59"]);
G2L["5c"]["TextWrapped"] = true;
G2L["5c"]["BorderSizePixel"] = 0;
G2L["5c"]["TextSize"] = 14;
G2L["5c"]["TextScaled"] = true;
G2L["5c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["5c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["BackgroundTransparency"] = 1;
G2L["5c"]["Size"] = UDim2.new(0, 133, 0, 29);
G2L["5c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5c"]["Text"] = [[Mostar Times]];
G2L["5c"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.m esp.TextLabel.LocalScript
G2L["5d"] = Instance.new("LocalScript", G2L["5c"]);



-- StarterGui.Painel do Mano.Menu.Visuais.d esp
G2L["5e"] = Instance.new("TextButton", G2L["49"]);
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextSize"] = 14;
G2L["5e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["5e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5e"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[]];
G2L["5e"]["Name"] = [[d esp]];
G2L["5e"]["Position"] = UDim2.new(0.01457, 0, 0.74212, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.d esp.LocalScript
G2L["5f"] = Instance.new("LocalScript", G2L["5e"]);



-- StarterGui.Painel do Mano.Menu.Visuais.d esp.UICorner
G2L["60"] = Instance.new("UICorner", G2L["5e"]);



-- StarterGui.Painel do Mano.Menu.Visuais.d esp.TextLabel
G2L["61"] = Instance.new("TextLabel", G2L["5e"]);
G2L["61"]["TextWrapped"] = true;
G2L["61"]["BorderSizePixel"] = 0;
G2L["61"]["TextSize"] = 14;
G2L["61"]["TextScaled"] = true;
G2L["61"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["61"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["61"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["61"]["BackgroundTransparency"] = 1;
G2L["61"]["Size"] = UDim2.new(0, 196, 0, 29);
G2L["61"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["61"]["Text"] = [[Mostar Distancia]];
G2L["61"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.d esp.TextLabel.LocalScript
G2L["62"] = Instance.new("LocalScript", G2L["61"]);



-- StarterGui.Painel do Mano.Menu.Visuais.mira fixa
G2L["63"] = Instance.new("TextButton", G2L["49"]);
G2L["63"]["BorderSizePixel"] = 0;
G2L["63"]["TextSize"] = 14;
G2L["63"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["63"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["63"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["63"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["63"]["Text"] = [[]];
G2L["63"]["Name"] = [[mira fixa]];
G2L["63"]["Position"] = UDim2.new(0.48079, 0, 0.03918, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.mira fixa.LocalScript
G2L["64"] = Instance.new("LocalScript", G2L["63"]);



-- StarterGui.Painel do Mano.Menu.Visuais.mira fixa.UICorner
G2L["65"] = Instance.new("UICorner", G2L["63"]);



-- StarterGui.Painel do Mano.Menu.Visuais.mira fixa.TextLabel
G2L["66"] = Instance.new("TextLabel", G2L["63"]);
G2L["66"]["TextWrapped"] = true;
G2L["66"]["BorderSizePixel"] = 0;
G2L["66"]["TextSize"] = 14;
G2L["66"]["TextScaled"] = true;
G2L["66"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["66"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["66"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["66"]["BackgroundTransparency"] = 1;
G2L["66"]["Size"] = UDim2.new(0, 135, 0, 29);
G2L["66"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["66"]["Text"] = [[Mira Fixa]];
G2L["66"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.mira fixa.TextLabel.LocalScript
G2L["67"] = Instance.new("LocalScript", G2L["66"]);



-- StarterGui.Painel do Mano.Menu.Visuais.SetFov
G2L["68"] = Instance.new("TextBox", G2L["49"]);
G2L["68"]["Name"] = [[SetFov]];
G2L["68"]["BorderSizePixel"] = 0;
G2L["68"]["TextWrapped"] = true;
G2L["68"]["TextSize"] = 14;
G2L["68"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["TextScaled"] = true;
G2L["68"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["68"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["68"]["PlaceholderText"] = [[Set Fov...]];
G2L["68"]["Size"] = UDim2.new(0, 213, 0, 32);
G2L["68"]["Position"] = UDim2.new(0.48079, 0, 0.35331, 0);
G2L["68"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["Text"] = [[]];


-- StarterGui.Painel do Mano.Menu.Visuais.SetFov.UICorner
G2L["69"] = Instance.new("UICorner", G2L["68"]);



-- StarterGui.Painel do Mano.Menu.Visuais.SetFov.LocalScript
G2L["6a"] = Instance.new("LocalScript", G2L["68"]);



-- StarterGui.Painel do Mano.Menu.Visuais.FOV
G2L["6b"] = Instance.new("TextButton", G2L["49"]);
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["TextSize"] = 14;
G2L["6b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["6b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6b"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Text"] = [[]];
G2L["6b"]["Name"] = [[FOV]];
G2L["6b"]["Position"] = UDim2.new(0.48079, 0, 0.20524, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.FOV.LocalScript
G2L["6c"] = Instance.new("LocalScript", G2L["6b"]);



-- StarterGui.Painel do Mano.Menu.Visuais.FOV.UICorner
G2L["6d"] = Instance.new("UICorner", G2L["6b"]);



-- StarterGui.Painel do Mano.Menu.Visuais.FOV.TextLabel
G2L["6e"] = Instance.new("TextLabel", G2L["6b"]);
G2L["6e"]["TextWrapped"] = true;
G2L["6e"]["BorderSizePixel"] = 0;
G2L["6e"]["TextSize"] = 14;
G2L["6e"]["TextScaled"] = true;
G2L["6e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6e"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6e"]["BackgroundTransparency"] = 1;
G2L["6e"]["Size"] = UDim2.new(0, 135, 0, 29);
G2L["6e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6e"]["Text"] = [[Mudar FOV]];
G2L["6e"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Visuais.FOV.TextLabel.LocalScript
G2L["6f"] = Instance.new("LocalScript", G2L["6e"]);



-- StarterGui.Painel do Mano.Menu.Fps
G2L["70"] = Instance.new("Frame", G2L["2"]);
G2L["70"]["Visible"] = false;
G2L["70"]["BorderSizePixel"] = 0;
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["70"]["Size"] = UDim2.new(0, 755, 0, 340);
G2L["70"]["Position"] = UDim2.new(0, 0, 0.21114, 0);
G2L["70"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["70"]["Name"] = [[Fps]];
G2L["70"]["BackgroundTransparency"] = 1;


-- StarterGui.Painel do Mano.Menu.Fps.eff
G2L["71"] = Instance.new("TextButton", G2L["70"]);
G2L["71"]["BorderSizePixel"] = 0;
G2L["71"]["TextSize"] = 14;
G2L["71"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["71"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["71"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["71"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["71"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["71"]["Text"] = [[]];
G2L["71"]["Name"] = [[eff]];
G2L["71"]["Position"] = UDim2.new(0.01457, 0, 0.03918, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
G2L["72"] = Instance.new("LocalScript", G2L["71"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.UICorner
G2L["73"] = Instance.new("UICorner", G2L["71"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel
G2L["74"] = Instance.new("TextLabel", G2L["71"]);
G2L["74"]["TextWrapped"] = true;
G2L["74"]["BorderSizePixel"] = 0;
G2L["74"]["TextSize"] = 14;
G2L["74"]["TextScaled"] = true;
G2L["74"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["74"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["74"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["74"]["BackgroundTransparency"] = 1;
G2L["74"]["Size"] = UDim2.new(0, 187, 0, 29);
G2L["74"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["74"]["Text"] = [[Desativar Efeitos]];
G2L["74"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
G2L["75"] = Instance.new("LocalScript", G2L["74"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff
G2L["76"] = Instance.new("TextButton", G2L["70"]);
G2L["76"]["BorderSizePixel"] = 0;
G2L["76"]["TextSize"] = 14;
G2L["76"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["76"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["76"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["76"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["76"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["76"]["Text"] = [[]];
G2L["76"]["Name"] = [[eff]];
G2L["76"]["Position"] = UDim2.new(0.01457, 0, 0.20977, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
G2L["77"] = Instance.new("LocalScript", G2L["76"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.UICorner
G2L["78"] = Instance.new("UICorner", G2L["76"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel
G2L["79"] = Instance.new("TextLabel", G2L["76"]);
G2L["79"]["TextWrapped"] = true;
G2L["79"]["BorderSizePixel"] = 0;
G2L["79"]["TextSize"] = 14;
G2L["79"]["TextScaled"] = true;
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["79"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["BackgroundTransparency"] = 1;
G2L["79"]["Size"] = UDim2.new(0, 208, 0, 29);
G2L["79"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["79"]["Text"] = [[Desativar Particulas]];
G2L["79"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
G2L["7a"] = Instance.new("LocalScript", G2L["79"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff
G2L["7b"] = Instance.new("TextButton", G2L["70"]);
G2L["7b"]["BorderSizePixel"] = 0;
G2L["7b"]["TextSize"] = 14;
G2L["7b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7b"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["7b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7b"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["7b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7b"]["Text"] = [[]];
G2L["7b"]["Name"] = [[eff]];
G2L["7b"]["Position"] = UDim2.new(0.01457, 0, 0.39506, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
G2L["7c"] = Instance.new("LocalScript", G2L["7b"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.UICorner
G2L["7d"] = Instance.new("UICorner", G2L["7b"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel
G2L["7e"] = Instance.new("TextLabel", G2L["7b"]);
G2L["7e"]["TextWrapped"] = true;
G2L["7e"]["BorderSizePixel"] = 0;
G2L["7e"]["TextSize"] = 14;
G2L["7e"]["TextScaled"] = true;
G2L["7e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7e"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["7e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7e"]["BackgroundTransparency"] = 1;
G2L["7e"]["Size"] = UDim2.new(0, 208, 0, 29);
G2L["7e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7e"]["Text"] = [[Desativar Sombras]];
G2L["7e"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
G2L["7f"] = Instance.new("LocalScript", G2L["7e"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff
G2L["80"] = Instance.new("TextButton", G2L["70"]);
G2L["80"]["BorderSizePixel"] = 0;
G2L["80"]["TextSize"] = 14;
G2L["80"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["80"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["80"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["80"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["80"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["80"]["Text"] = [[]];
G2L["80"]["Name"] = [[eff]];
G2L["80"]["Position"] = UDim2.new(0.01457, 0, 0.57741, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
G2L["81"] = Instance.new("LocalScript", G2L["80"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.UICorner
G2L["82"] = Instance.new("UICorner", G2L["80"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel
G2L["83"] = Instance.new("TextLabel", G2L["80"]);
G2L["83"]["TextWrapped"] = true;
G2L["83"]["BorderSizePixel"] = 0;
G2L["83"]["TextSize"] = 14;
G2L["83"]["TextScaled"] = true;
G2L["83"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["83"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["83"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["83"]["BackgroundTransparency"] = 1;
G2L["83"]["Size"] = UDim2.new(0, 208, 0, 29);
G2L["83"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["83"]["Text"] = [[Desativar Materiais]];
G2L["83"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
G2L["84"] = Instance.new("LocalScript", G2L["83"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff
G2L["85"] = Instance.new("TextButton", G2L["70"]);
G2L["85"]["BorderSizePixel"] = 0;
G2L["85"]["TextSize"] = 14;
G2L["85"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["85"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["85"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["85"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["85"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["85"]["Text"] = [[]];
G2L["85"]["Name"] = [[eff]];
G2L["85"]["Position"] = UDim2.new(0.01457, 0, 0.76565, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
G2L["86"] = Instance.new("LocalScript", G2L["85"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.UICorner
G2L["87"] = Instance.new("UICorner", G2L["85"]);



-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel
G2L["88"] = Instance.new("TextLabel", G2L["85"]);
G2L["88"]["TextWrapped"] = true;
G2L["88"]["BorderSizePixel"] = 0;
G2L["88"]["TextSize"] = 14;
G2L["88"]["TextScaled"] = true;
G2L["88"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["88"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["88"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["88"]["BackgroundTransparency"] = 1;
G2L["88"]["Size"] = UDim2.new(0, 148, 0, 29);
G2L["88"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["88"]["Text"] = [[Modo Batata]];
G2L["88"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
G2L["89"] = Instance.new("LocalScript", G2L["88"]);



-- StarterGui.Painel do Mano.Menu.Fps.FPSDisplay
G2L["8a"] = Instance.new("TextLabel", G2L["70"]);
G2L["8a"]["TextWrapped"] = true;
G2L["8a"]["BorderSizePixel"] = 0;
G2L["8a"]["TextSize"] = 14;
G2L["8a"]["TextScaled"] = true;
G2L["8a"]["BackgroundColor3"] = Color3.fromRGB(49, 192, 199);
G2L["8a"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["8a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8a"]["Size"] = UDim2.new(0, 140, 0, 41);
G2L["8a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8a"]["Text"] = [[0]];
G2L["8a"]["Name"] = [[FPSDisplay]];
G2L["8a"]["Position"] = UDim2.new(0.40643, 0, 0.14818, 0);


-- StarterGui.Painel do Mano.Menu.Fps.FPSDisplay.LocalScript
G2L["8b"] = Instance.new("LocalScript", G2L["8a"]);



-- StarterGui.Painel do Mano.Menu.Fps.FPSDisplay.UICorner
G2L["8c"] = Instance.new("UICorner", G2L["8a"]);



-- StarterGui.Painel do Mano.Menu.Fps.FPSDisplay.LocalScript
G2L["8d"] = Instance.new("LocalScript", G2L["8a"]);



-- StarterGui.Painel do Mano.Menu.Fps.TextLabel
G2L["8e"] = Instance.new("TextLabel", G2L["70"]);
G2L["8e"]["TextWrapped"] = true;
G2L["8e"]["BorderSizePixel"] = 0;
G2L["8e"]["TextSize"] = 14;
G2L["8e"]["TextScaled"] = true;
G2L["8e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8e"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["8e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8e"]["BackgroundTransparency"] = 1;
G2L["8e"]["Size"] = UDim2.new(0, 115, 0, 38);
G2L["8e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8e"]["Text"] = [[FPS]];
G2L["8e"]["Position"] = UDim2.new(0.42384, 0, 0.03771, 0);


-- StarterGui.Painel do Mano.Menu.Fps.TextLabel.LocalScript
G2L["8f"] = Instance.new("LocalScript", G2L["8e"]);



-- StarterGui.Painel do Mano.Menu.Outers
G2L["90"] = Instance.new("Frame", G2L["2"]);
G2L["90"]["BorderSizePixel"] = 0;
G2L["90"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["90"]["Size"] = UDim2.new(0, 755, 0, 340);
G2L["90"]["Position"] = UDim2.new(0, 0, 0.21114, 0);
G2L["90"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["90"]["Name"] = [[Outers]];
G2L["90"]["BackgroundTransparency"] = 1;


-- StarterGui.Painel do Mano.Menu.Outers.TextLabel
G2L["91"] = Instance.new("TextLabel", G2L["90"]);
G2L["91"]["TextWrapped"] = true;
G2L["91"]["BorderSizePixel"] = 0;
G2L["91"]["TextSize"] = 14;
G2L["91"]["TextScaled"] = true;
G2L["91"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["91"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["91"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["91"]["BackgroundTransparency"] = 1;
G2L["91"]["Size"] = UDim2.new(0, 212, 0, 44);
G2L["91"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["91"]["Text"] = [[Painel Fornecido Por:]];
G2L["91"]["Position"] = UDim2.new(0.02781, 0, 0.03771, 0);


-- StarterGui.Painel do Mano.Menu.Outers.Pedrinhuu On Top
G2L["92"] = Instance.new("TextLabel", G2L["90"]);
G2L["92"]["TextWrapped"] = true;
G2L["92"]["BorderSizePixel"] = 0;
G2L["92"]["TextSize"] = 14;
G2L["92"]["TextScaled"] = true;
G2L["92"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["92"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["92"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["92"]["BackgroundTransparency"] = 1;
G2L["92"]["Size"] = UDim2.new(0, 269, 0, 51);
G2L["92"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["92"]["Text"] = [[Pedrinhuu Scripts]];
G2L["92"]["Name"] = [[Pedrinhuu On Top]];
G2L["92"]["Position"] = UDim2.new(0.02781, 0, 0.14947, 0);


-- StarterGui.Painel do Mano.Menu.Outers.Pedrinhuu On Top.LocalScript
G2L["93"] = Instance.new("LocalScript", G2L["92"]);



-- StarterGui.Painel do Mano.Menu.Outers.Change Title
G2L["94"] = Instance.new("TextLabel", G2L["90"]);
G2L["94"]["TextWrapped"] = true;
G2L["94"]["BorderSizePixel"] = 0;
G2L["94"]["TextSize"] = 14;
G2L["94"]["TextScaled"] = true;
G2L["94"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["94"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["94"]["TextColor3"] = Color3.fromRGB(49, 192, 199);
G2L["94"]["BackgroundTransparency"] = 1;
G2L["94"]["Size"] = UDim2.new(0, 343, 0, 30);
G2L["94"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["94"]["Text"] = [[-=======- CHANGE LOGS -=======-]];
G2L["94"]["Name"] = [[Change Title]];
G2L["94"]["Position"] = UDim2.new(0.50993, 0, 0.03771, 0);


-- StarterGui.Painel do Mano.Menu.Outers.TextLabel
G2L["95"] = Instance.new("TextLabel", G2L["90"]);
G2L["95"]["TextWrapped"] = true;
G2L["95"]["BorderSizePixel"] = 0;
G2L["95"]["TextSize"] = 14;
G2L["95"]["TextScaled"] = true;
G2L["95"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["95"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["95"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["95"]["BackgroundTransparency"] = 1;
G2L["95"]["Size"] = UDim2.new(0, 302, 0, 38);
G2L["95"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["95"]["Text"] = [[Painel Não Atualizado Ainda]];
G2L["95"]["Position"] = UDim2.new(0.54702, 0, 0.14947, 0);


-- StarterGui.Painel do Mano.Menu.Outers.TextLabel
G2L["96"] = Instance.new("TextLabel", G2L["90"]);
G2L["96"]["TextWrapped"] = true;
G2L["96"]["BorderSizePixel"] = 0;
G2L["96"]["TextSize"] = 14;
G2L["96"]["TextTransparency"] = 0.58;
G2L["96"]["TextScaled"] = true;
G2L["96"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["96"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["96"]["TextColor3"] = Color3.fromRGB(49, 192, 199);
G2L["96"]["BackgroundTransparency"] = 1;
G2L["96"]["Size"] = UDim2.new(0, 104, 0, 23);
G2L["96"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["96"]["Text"] = [[Version: V1]];
G2L["96"]["Position"] = UDim2.new(0.05298, 0, 0.89653, 0);


-- StarterGui.Painel do Mano.Menu.Outers.TextLabel
G2L["97"] = Instance.new("TextLabel", G2L["90"]);
G2L["97"]["TextWrapped"] = true;
G2L["97"]["BorderSizePixel"] = 0;
G2L["97"]["TextSize"] = 14;
G2L["97"]["TextTransparency"] = 0.58;
G2L["97"]["TextScaled"] = true;
G2L["97"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["97"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["97"]["TextColor3"] = Color3.fromRGB(49, 192, 199);
G2L["97"]["BackgroundTransparency"] = 1;
G2L["97"]["Size"] = UDim2.new(0, 169, 0, 23);
G2L["97"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["97"]["Text"] = [[Criado em 15/02/2026]];
G2L["97"]["Position"] = UDim2.new(0.21722, 0, 0.89653, 0);


-- StarterGui.Painel do Mano.Menu.Outers.TextLabel
G2L["98"] = Instance.new("TextLabel", G2L["90"]);
G2L["98"]["TextWrapped"] = true;
G2L["98"]["BorderSizePixel"] = 0;
G2L["98"]["TextSize"] = 14;
G2L["98"]["TextTransparency"] = 0.58;
G2L["98"]["TextScaled"] = true;
G2L["98"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["98"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["98"]["TextColor3"] = Color3.fromRGB(49, 192, 199);
G2L["98"]["BackgroundTransparency"] = 1;
G2L["98"]["Size"] = UDim2.new(0, 169, 0, 23);
G2L["98"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["98"]["Text"] = [[Atualizado: Sem Updates]];
G2L["98"]["Position"] = UDim2.new(0.4649, 0, 0.89653, 0);


-- StarterGui.Painel do Mano.Menu.Outers.TextLabel
G2L["99"] = Instance.new("TextLabel", G2L["90"]);
G2L["99"]["TextWrapped"] = true;
G2L["99"]["BorderSizePixel"] = 0;
G2L["99"]["TextSize"] = 14;
G2L["99"]["TextTransparency"] = 0.58;
G2L["99"]["TextScaled"] = true;
G2L["99"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["99"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["99"]["TextColor3"] = Color3.fromRGB(49, 192, 199);
G2L["99"]["BackgroundTransparency"] = 1;
G2L["99"]["Size"] = UDim2.new(0, 169, 0, 23);
G2L["99"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["99"]["Text"] = [[PEDRINHUU ON TOP 👑]];
G2L["99"]["Position"] = UDim2.new(0.72185, 0, 0.89653, 0);


-- StarterGui.Painel do Mano.Menu.Close
G2L["9a"] = Instance.new("TextButton", G2L["2"]);
G2L["9a"]["BorderSizePixel"] = 0;
G2L["9a"]["TextSize"] = 32;
G2L["9a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9a"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9a"]["BackgroundTransparency"] = 1;
G2L["9a"]["Size"] = UDim2.new(0, 43, 0, 33);
G2L["9a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9a"]["Text"] = [[X]];
G2L["9a"]["Name"] = [[Close]];
G2L["9a"]["Position"] = UDim2.new(0.94305, 0, 0.00232, 0);


-- StarterGui.Painel do Mano.Menu.Close.LocalScript
G2L["9b"] = Instance.new("LocalScript", G2L["9a"]);



-- StarterGui.Painel do Mano.Menu.Min
G2L["9c"] = Instance.new("TextButton", G2L["2"]);
G2L["9c"]["TextWrapped"] = true;
G2L["9c"]["RichText"] = true;
G2L["9c"]["BorderSizePixel"] = 0;
G2L["9c"]["TextSize"] = 59;
G2L["9c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9c"]["BackgroundTransparency"] = 1;
G2L["9c"]["Size"] = UDim2.new(0, 36, 0, 33);
G2L["9c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9c"]["Text"] = [[-]];
G2L["9c"]["Name"] = [[Min]];
G2L["9c"]["Position"] = UDim2.new(0.89536, 0, 0, 0);


-- StarterGui.Painel do Mano.Menu.Min.LocalScript
G2L["9d"] = Instance.new("LocalScript", G2L["9c"]);



-- StarterGui.Painel do Mano.Open
G2L["9e"] = Instance.new("ImageButton", G2L["1"]);
G2L["9e"]["BorderSizePixel"] = 0;
G2L["9e"]["Visible"] = false;
G2L["9e"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9e"]["Image"] = [[rbxassetid://13321848320]];
G2L["9e"]["Size"] = UDim2.new(0, 51, 0, 51);
G2L["9e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9e"]["Name"] = [[Open]];
G2L["9e"]["Position"] = UDim2.new(0.2186, 0, 0.48391, 0);


-- StarterGui.Painel do Mano.Open. botao
G2L["9f"] = Instance.new("LocalScript", G2L["9e"]);
G2L["9f"]["Name"] = [[ botao]];


-- StarterGui.Painel do Mano.Open.LocalScript
G2L["a0"] = Instance.new("LocalScript", G2L["9e"]);



-- StarterGui.Painel do Mano.Open.UICorner
G2L["a1"] = Instance.new("UICorner", G2L["9e"]);
G2L["a1"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.Painel do Mano.Menu.Drag
local function C_3()
local script = G2L["3"];
	local UserInputService = game:GetService("UserInputService")
	local player = game.Players.LocalPlayer
	local gui = player:WaitForChild("PlayerGui")
	local frame = script.Parent -- Coloque o LocalScript dentro do Frame que será arrastável
	
	local dragging = false
	local dragInput, dragStart, startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale,
			startPos.X.Offset + delta.X,
			startPos.Y.Scale,
			startPos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
	
end;
task.spawn(C_3);
-- StarterGui.Painel do Mano.Menu.Buttons.Aim.LocalScript
local function C_9()
local script = G2L["9"];
	local button = script.Parent
	local buttonsFrame = button.Parent
	local screenGui = buttonsFrame.Parent
	
	local aimFrame = screenGui:WaitForChild("AimFrame")
	local fpsFrame = screenGui:WaitForChild("Fps")
	local outersFrame = screenGui:WaitForChild("Outers")
	local visualsFrame = screenGui:WaitForChild("Visuais")
	
	local frames = {aimFrame, fpsFrame, outersFrame, visualsFrame}
	
	button.MouseButton1Click:Connect(function()
		for _, frame in ipairs(frames) do
			frame.Visible = false
		end
	
		aimFrame.Visible = true
	end)
end;
task.spawn(C_9);
-- StarterGui.Painel do Mano.Menu.Buttons.Aim.LocalScript
local function C_b()
local script = G2L["b"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_b);
-- StarterGui.Painel do Mano.Menu.Buttons.Visual.LocalScript
local function C_d()
local script = G2L["d"];
	local button = script.Parent
	local buttonsFrame = button.Parent
	local screenGui = buttonsFrame.Parent
	
	local aimFrame = screenGui:WaitForChild("AimFrame")
	local fpsFrame = screenGui:WaitForChild("Fps")
	local outersFrame = screenGui:WaitForChild("Outers")
	local visualsFrame = screenGui:WaitForChild("Visuais")
	
	local frames = {aimFrame, fpsFrame, outersFrame, visualsFrame}
	
	button.MouseButton1Click:Connect(function()
		for _, frame in ipairs(frames) do
			frame.Visible = false
		end
	
		visualsFrame.Visible = true
	end)
end;
task.spawn(C_d);
-- StarterGui.Painel do Mano.Menu.Buttons.Visual.LocalScript
local function C_f()
local script = G2L["f"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_f);
-- StarterGui.Painel do Mano.Menu.Buttons.FPS.LocalScript
local function C_11()
local script = G2L["11"];
	local button = script.Parent
	local buttonsFrame = button.Parent
	local screenGui = buttonsFrame.Parent
	
	local aimFrame = screenGui:WaitForChild("AimFrame")
	local fpsFrame = screenGui:WaitForChild("Fps")
	local outersFrame = screenGui:WaitForChild("Outers")
	local visualsFrame = screenGui:WaitForChild("Visuais")
	
	local frames = {aimFrame, fpsFrame, outersFrame, visualsFrame}
	
	button.MouseButton1Click:Connect(function()
		for _, frame in ipairs(frames) do
			frame.Visible = false
		end
	
		fpsFrame.Visible = true
	end)
end;
task.spawn(C_11);
-- StarterGui.Painel do Mano.Menu.Buttons.FPS.LocalScript
local function C_13()
local script = G2L["13"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_13);
-- StarterGui.Painel do Mano.Menu.Buttons.Outros.LocalScript
local function C_15()
local script = G2L["15"];
	local button = script.Parent
	local buttonsFrame = button.Parent
	local screenGui = buttonsFrame.Parent
	
	local aimFrame = screenGui:WaitForChild("AimFrame")
	local fpsFrame = screenGui:WaitForChild("Fps")
	local outersFrame = screenGui:WaitForChild("Outers")
	local visualsFrame = screenGui:WaitForChild("Visuais")
	
	local frames = {aimFrame, fpsFrame, outersFrame, visualsFrame}
	
	button.MouseButton1Click:Connect(function()
		for _, frame in ipairs(frames) do
			frame.Visible = false
		end
	
		outersFrame.Visible = true
	end)
end;
task.spawn(C_15);
-- StarterGui.Painel do Mano.Menu.Buttons.Outros.LocalScript
local function C_17()
local script = G2L["17"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_17);
-- StarterGui.Painel do Mano.Menu.AimFrame.aimbut.LocalScript
local function C_1a()
local script = G2L["1a"];
	----------------------------------------------------
	-- SERVICES
	----------------------------------------------------
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local LocalPlayer = Players.LocalPlayer
	local Camera = workspace.CurrentCamera
	
	----------------------------------------------------
	-- UI REFERENCES
	----------------------------------------------------
	local root = script.Parent.Parent -- ajuste se necessário
	
	local toggleButton = script.Parent
	local setButton = root:WaitForChild("Set")
	local npcButton = root:WaitForChild("NPC")
	local tcButton = root:WaitForChild("TC")
	
	local forceBox = root:WaitForChild("Force")
	local distanceBox = root:WaitForChild("Distance")
	local rangeBox = root:WaitForChild("Range")
	
	----------------------------------------------------
	-- CONFIGS (PADRÃO)
	----------------------------------------------------
	local MAX_PIXELS = 150
	local AIM_SMOOTH = 0.87
	local MAX_STUDS = 300
	
	local SCAN_NPCS = true
	local IGNORE_TEAM = false -- Team Check inicia OFF
	
	----------------------------------------------------
	-- SYSTEM STATE
	----------------------------------------------------
	local active = false
	local connection = nil
	local ui = nil
	
	----------------------------------------------------
	-- INIT UI TEXT
	----------------------------------------------------
	npcButton.Text = "NPC: ON"
	tcButton.Text = "Team Check: OFF"
	
	----------------------------------------------------
	-- UTILS
	----------------------------------------------------
	local function clampNumber(value, min, max)
		value = tonumber(value)
		if not value then return nil end
		return math.clamp(value, min, max)
	end
	
	----------------------------------------------------
	-- UI (DOT + CIRCLE)
	----------------------------------------------------
	local function createDot()
		if ui then return end
	
		local g = Instance.new("ScreenGui")
		g.IgnoreGuiInset = true
		g.ResetOnSpawn = false
		g.Name = "CenterDotGui"
		g.Parent = LocalPlayer:WaitForChild("PlayerGui")
	
		local dot = Instance.new("Frame")
		dot.AnchorPoint = Vector2.new(0.5, 0.5)
		dot.Size = UDim2.new(0, 6, 0, 6)
		dot.Position = UDim2.fromScale(0.5, 0.5)
		dot.BackgroundColor3 = Color3.new(1, 1, 1)
		dot.BorderSizePixel = 0
		dot.Parent = g
	
		local circle = Instance.new("Frame")
		circle.Name = "AimRadius"
		circle.AnchorPoint = Vector2.new(0.5, 0.5)
		circle.BackgroundTransparency = 1
		circle.Size = UDim2.new(0, MAX_PIXELS * 2, 0, MAX_PIXELS * 2)
		circle.Position = UDim2.fromScale(0.5, 0.5)
		circle.Parent = g
	
		local stroke = Instance.new("UIStroke")
		stroke.Thickness = 2
		stroke.Color = Color3.new(1, 1, 1)
		stroke.Transparency = 0.4
		stroke.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
		stroke.Parent = circle
	
		local corner = Instance.new("UICorner")
		corner.CornerRadius = UDim.new(1, 0)
		corner.Parent = circle
	
		ui = g
	end
	
	local function updateCircle()
		if not ui then return end
		local circle = ui:FindFirstChild("AimRadius", true)
		if circle then
			circle.Size = UDim2.new(0, MAX_PIXELS * 2, 0, MAX_PIXELS * 2)
		end
	end
	
	local function removeDot()
		if ui then
			ui:Destroy()
			ui = nil
		end
	end
	
	----------------------------------------------------
	-- TARGETS
	----------------------------------------------------
	local function getTargets()
		local list = {}
	
		-- Players
		for _, plr in ipairs(Players:GetPlayers()) do
			if plr ~= LocalPlayer and plr.Character then
				if IGNORE_TEAM and LocalPlayer.Team ~= nil then
					if plr.Team ~= LocalPlayer.Team then
						table.insert(list, plr.Character)
					end
				else
					table.insert(list, plr.Character)
				end
			end
		end
	
		-- NPCs
		if SCAN_NPCS then
			for _, obj in ipairs(workspace:GetChildren()) do
				if obj:IsA("Model")
					and obj:FindFirstChild("Humanoid")
					and obj:FindFirstChild("Head")
					and not Players:GetPlayerFromCharacter(obj) then
					table.insert(list, obj)
				end
			end
		end
	
		return list
	end
	
	----------------------------------------------------
	-- AIMLOCK CORE
	----------------------------------------------------
	local function getClosestTarget()
		local viewport = Camera.ViewportSize
		local center = Vector2.new(viewport.X / 2, viewport.Y / 2)
	
		local bestPart = nil
		local bestDist = MAX_PIXELS + 0.01
	
		for _, char in ipairs(getTargets()) do
			local head = char:FindFirstChild("Head")
			local hum = char:FindFirstChild("Humanoid")
	
			if head and hum and hum.Health > 0 then
				if (Camera.CFrame.Position - head.Position).Magnitude <= MAX_STUDS then
					local pos = Camera:WorldToViewportPoint(head.Position)
					if pos.Z > 0 then
						local dist = (Vector2.new(pos.X, pos.Y) - center).Magnitude
						if dist < bestDist then
							bestDist = dist
							bestPart = head
						end
					end
				end
			end
		end
	
		return bestPart
	end
	
	----------------------------------------------------
	-- START / STOP
	----------------------------------------------------
	local function startSystem()
		if active then return end
		active = true
	
		createDot()
	
		connection = RunService.RenderStepped:Connect(function()
			if not active then return end
	
			local target = getClosestTarget()
			if target then
				local current = Camera.CFrame
				local goal = CFrame.lookAt(current.Position, target.Position)
				Camera.CFrame = current:Lerp(goal, AIM_SMOOTH)
			end
		end)
	end
	
	local function stopSystem()
		active = false
	
		if connection then
			connection:Disconnect()
			connection = nil
		end
	
		removeDot()
	end
	
	----------------------------------------------------
	-- BUTTONS
	----------------------------------------------------
	toggleButton.MouseButton1Click:Connect(function()
		if active then
			stopSystem()
		else
			startSystem()
		end
	end)
	
	npcButton.MouseButton1Click:Connect(function()
		SCAN_NPCS = not SCAN_NPCS
		npcButton.Text = SCAN_NPCS and "NPC: ON" or "NPC: OFF"
	end)
	
	tcButton.MouseButton1Click:Connect(function()
		IGNORE_TEAM = not IGNORE_TEAM
		tcButton.Text = IGNORE_TEAM and "Team Check: ON" or "Team Check: OFF"
	end)
	
	setButton.MouseButton1Click:Connect(function()
		local force = clampNumber(forceBox.Text, 0, 1)
		if force then AIM_SMOOTH = force end
	
		local pixels = clampNumber(distanceBox.Text, 0, 500)
		if pixels then
			MAX_PIXELS = pixels
			updateCircle()
		end
	
		local studs = clampNumber(rangeBox.Text, 0, 1000)
		if studs then MAX_STUDS = studs end
	
		forceBox:ReleaseFocus()
		distanceBox:ReleaseFocus()
		rangeBox:ReleaseFocus()
	end)
	
end;
task.spawn(C_1a);
-- StarterGui.Painel do Mano.Menu.AimFrame.aimbut.TextLabel.LocalScript
local function C_1d()
local script = G2L["1d"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_1d);
-- StarterGui.Painel do Mano.Menu.AimFrame.aimlock.LocalScript
local function C_1f()
local script = G2L["1f"];
	------------------------------------------------
	-- SERVICES
	------------------------------------------------
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local player = Players.LocalPlayer
	local playerGui = player:WaitForChild("PlayerGui")
	local camera = workspace.CurrentCamera
	
	------------------------------------------------
	-- UI REFERENCES
	------------------------------------------------
	local root = script.Parent.Parent
	local mainButton = script.Parent
	local tcButton = root:WaitForChild("TC")
	local npcButton = root:WaitForChild("NPC")
	
	------------------------------------------------
	-- CONFIG
	------------------------------------------------
	local DOT_SIZE = 8
	local DOT_COLOR = Color3.fromRGB(255, 20, 20)
	
	local AIM_RADIUS = 25
	local SMOOTHNESS = 0.70
	_G.AimTargetPart = "Head"
	
	------------------------------------------------
	-- STATES
	------------------------------------------------
	local TEAM_CHECK = false
	local SCAN_NPCS = true
	
	tcButton.Text = "Team Check: OFF"
	npcButton.Text = "NPC: ON"
	
	------------------------------------------------
	-- CENTER DOT (SIMPLES E SEGURO)
	------------------------------------------------
	local gui = Instance.new("ScreenGui")
	gui.Name = "CenterDotGui"
	gui.ResetOnSpawn = false
	gui.IgnoreGuiInset = true
	gui.Parent = playerGui
	
	local dot = Instance.new("Frame")
	dot.Size = UDim2.fromOffset(DOT_SIZE, DOT_SIZE)
	dot.AnchorPoint = Vector2.new(0.5, 0.5)
	dot.Position = UDim2.fromScale(0.5, 0.5)
	dot.BackgroundColor3 = DOT_COLOR
	dot.BorderSizePixel = 0
	dot.Visible = false
	dot.Active = false
	dot.Parent = gui
	Instance.new("UICorner", dot).CornerRadius = UDim.new(1, 0)
	
	------------------------------------------------
	-- TARGET SYSTEM
	------------------------------------------------
	local function isValidPlayer(model)
		local plr = Players:GetPlayerFromCharacter(model)
		if not plr or plr == player then return false end
		if TEAM_CHECK and player.Team then
			return plr.Team ~= player.Team
		end
		return true
	end
	
	local function getClosestTarget()
		local closest
		local shortest = AIM_RADIUS
		local center = camera.ViewportSize / 2
	
		for _, model in ipairs(workspace:GetChildren()) do
			if model:IsA("Model") and model ~= player.Character then
				local hum = model:FindFirstChildOfClass("Humanoid")
				local part = model:FindFirstChild(_G.AimTargetPart)
	
				if hum and hum.Health > 0 and part then
					local isPlayer = Players:GetPlayerFromCharacter(model)
	
					if (isPlayer and isValidPlayer(model)) or (not isPlayer and SCAN_NPCS) then
						local pos, onscreen = camera:WorldToViewportPoint(part.Position)
						if onscreen then
							local dist = (Vector2.new(pos.X, pos.Y) - center).Magnitude
							if dist < shortest then
								shortest = dist
								closest = part
							end
						end
					end
				end
			end
		end
	
		return closest
	end
	
	------------------------------------------------
	-- LOOP
	------------------------------------------------
	RunService.RenderStepped:Connect(function()
		if not dot.Visible then return end
	
		local target = getClosestTarget()
		if target then
			local camPos = camera.CFrame.Position
			camera.CFrame = camera.CFrame:Lerp(
				CFrame.new(camPos, target.Position),
				SMOOTHNESS
			)
		end
	end)
	
	------------------------------------------------
	-- BUTTONS (UM EVENTO CADA)
	------------------------------------------------
	mainButton.Activated:Connect(function()
		dot.Visible = not dot.Visible
	end)
	
	tcButton.Activated:Connect(function()
		TEAM_CHECK = not TEAM_CHECK
		tcButton.Text = TEAM_CHECK and "Team Check: ON" or "Team Check: OFF"
	end)
	
	npcButton.Activated:Connect(function()
		SCAN_NPCS = not SCAN_NPCS
		npcButton.Text = SCAN_NPCS and "NPC: ON" or "NPC: OFF"
	end)
	
end;
task.spawn(C_1f);
-- StarterGui.Painel do Mano.Menu.AimFrame.aimlock.TextLabel.LocalScript
local function C_22()
local script = G2L["22"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_22);
-- StarterGui.Painel do Mano.Menu.AimFrame.auxilio.LocalScript
local function C_24()
local script = G2L["24"];
	-- Aim Assist do PEDRINHUU (ATUALIZADO COM TC + NPC)
	
	------------------------------------------------
	-- SERVICES
	------------------------------------------------
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local player = Players.LocalPlayer
	local playerGui = player:WaitForChild("PlayerGui")
	local camera = workspace.CurrentCamera
	
	------------------------------------------------
	-- UI REFERENCES
	------------------------------------------------
	local root = script.Parent.Parent
	local mainButton = script.Parent
	local tcButton = root:WaitForChild("TC")
	local npcButton = root:WaitForChild("NPC")
	
	------------------------------------------------
	-- CONFIG
	------------------------------------------------
	local DOT_SIZE = 8
	local DOT_COLOR = Color3.fromRGB(255, 20, 20)
	
	local ASSIST_RANGE = 600
	local ASSIST_SMOOTH = 0.25
	
	------------------------------------------------
	-- STATE
	------------------------------------------------
	local active = false
	local connection
	
	local TEAM_CHECK = false -- inicia OFF
	local ENABLE_NPCS = true -- inicia ON
	
	------------------------------------------------
	-- INIT BUTTON TEXT
	------------------------------------------------
	tcButton.Text = "Team Check: OFF"
	npcButton.Text = "NPC: ON"
	
	------------------------------------------------
	-- CENTER DOT
	------------------------------------------------
	local gui = Instance.new("ScreenGui")
	gui.Name = "CenterDotGui"
	gui.ResetOnSpawn = false
	gui.DisplayOrder = 1000
	gui.IgnoreGuiInset = true
	gui.Parent = playerGui
	
	local dot = Instance.new("Frame")
	dot.Name = "CenterDot"
	dot.Size = UDim2.fromOffset(DOT_SIZE, DOT_SIZE)
	dot.AnchorPoint = Vector2.new(0.5, 0.5)
	dot.Position = UDim2.fromScale(0.5, 0.5)
	dot.BackgroundColor3 = DOT_COLOR
	dot.BorderSizePixel = 0
	dot.Visible = false
	dot.ZIndex = 9999
	dot.Parent = gui
	
	Instance.new("UICorner", dot).CornerRadius = UDim.new(1, 0)
	
	------------------------------------------------
	-- RAYCAST PARAMS
	------------------------------------------------
	local rayParams = RaycastParams.new()
	rayParams.FilterType = Enum.RaycastFilterType.Blacklist
	rayParams.IgnoreWater = true
	
	------------------------------------------------
	-- VALIDATION
	------------------------------------------------
	local function isValidTarget(model)
		local humanoid = model:FindFirstChildOfClass("Humanoid")
		if not humanoid or humanoid.Health <= 0 then
			return false
		end
	
		local plr = Players:GetPlayerFromCharacter(model)
	
		-- NPC
		if not plr then
			return ENABLE_NPCS
		end
	
		-- Player
		if plr == player then
			return false
		end
	
		if TEAM_CHECK and player.Team ~= nil then
			return plr.Team ~= player.Team
		end
	
		return true
	end
	
	------------------------------------------------
	-- AIM ASSIST
	------------------------------------------------
	local function aimAssist()
		local viewport = camera.ViewportSize
		local center = Vector2.new(viewport.X / 2, viewport.Y / 2)
	
		local ray = camera:ViewportPointToRay(center.X, center.Y)
		rayParams.FilterDescendantsInstances = { player.Character }
	
		local result = workspace:Raycast(ray.Origin, ray.Direction * ASSIST_RANGE, rayParams)
		if not result then return end
	
		local hitPart = result.Instance
		if not hitPart then return end
	
		local model = hitPart:FindFirstAncestorOfClass("Model")
		if not model then return end
	
		if not isValidTarget(model) then return end
	
		local camPos = camera.CFrame.Position
		local targetCF = CFrame.new(camPos, hitPart.Position)
	
		camera.CFrame = camera.CFrame:Lerp(targetCF, ASSIST_SMOOTH)
	end
	
	------------------------------------------------
	-- LOOP
	------------------------------------------------
	local function start()
		if active then return end
		active = true
		dot.Visible = true
	
		connection = RunService.RenderStepped:Connect(function()
			if active then
				aimAssist()
			end
		end)
	end
	
	local function stop()
		active = false
		dot.Visible = false
	
		if connection then
			connection:Disconnect()
			connection = nil
		end
	end
	
	------------------------------------------------
	-- BUTTONS
	------------------------------------------------
	mainButton.Activated:Connect(function()
		if active then
			stop()
		else
			start()
		end
	end)
	
	tcButton.MouseButton1Click:Connect(function()
		TEAM_CHECK = not TEAM_CHECK
		tcButton.Text = TEAM_CHECK and "Team Check: ON" or "Team Check: OFF"
	end)
	
	npcButton.MouseButton1Click:Connect(function()
		ENABLE_NPCS = not ENABLE_NPCS
		npcButton.Text = ENABLE_NPCS and "NPC: ON" or "NPC: OFF"
	end)
	
end;
task.spawn(C_24);
-- StarterGui.Painel do Mano.Menu.AimFrame.auxilio.TextLabel.LocalScript
local function C_27()
local script = G2L["27"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_27);
-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel.LocalScript
local function C_2c()
local script = G2L["2c"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_2c);
-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel.LocalScript
local function C_30()
local script = G2L["30"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_30);
-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel.LocalScript
local function C_34()
local script = G2L["34"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_34);
-- StarterGui.Painel do Mano.Menu.AimFrame.Set.LocalScript
local function C_37()
local script = G2L["37"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_37);
-- StarterGui.Painel do Mano.Menu.AimFrame.Cabeca.LocalScript
local function C_3a()
local script = G2L["3a"];
	script.Parent.Activated:Connect(function()
		_G.AimTargetPart = "Head"
	end)
	
end;
task.spawn(C_3a);
-- StarterGui.Painel do Mano.Menu.AimFrame.Cabeca.LocalScript
local function C_3c()
local script = G2L["3c"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_3c);
-- StarterGui.Painel do Mano.Menu.AimFrame.TextLabel.LocalScript
local function C_3e()
local script = G2L["3e"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_3e);
-- StarterGui.Painel do Mano.Menu.AimFrame.Corpo.LocalScript
local function C_40()
local script = G2L["40"];
	script.Parent.Activated:Connect(function()
		_G.AimTargetPart = "Torso"
	end)
	
end;
task.spawn(C_40);
-- StarterGui.Painel do Mano.Menu.AimFrame.Corpo.LocalScript
local function C_42()
local script = G2L["42"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_42);
-- StarterGui.Painel do Mano.Menu.AimFrame.NPC.LocalScript
local function C_45()
local script = G2L["45"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_45);
-- StarterGui.Painel do Mano.Menu.AimFrame.TC.LocalScript
local function C_48()
local script = G2L["48"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_48);
-- StarterGui.Painel do Mano.Menu.Visuais.esp.LocalScript
local function C_4b()
local script = G2L["4b"];
	local Players = game:GetService("Players")
	local Workspace = game:GetService("Workspace")
	
	local button = script.Parent
	local localPlayer = Players.LocalPlayer
	local espEnabled = false
	local highlights = {}
	
	-- Função para verificar se é um personagem válido
	local function isValidCharacter(model)
		return model:FindFirstChild("Humanoid") and model:FindFirstChild("HumanoidRootPart")
	end
	
	-- Função para criar ESP em um modelo
	local function createESP(model)
		if model == localPlayer.Character then return end
		if highlights[model] then return end
	
		local highlight = Instance.new("Highlight")
		highlight.Name = "ESP_Highlight"
		highlight.FillColor = Color3.fromRGB(255, 0, 0)
		highlight.OutlineColor = Color3.fromRGB(255, 255, 255)
		highlight.FillTransparency = 0.5
		highlight.OutlineTransparency = 0
		highlight.Parent = model
	
		highlights[model] = highlight
	end
	
	-- Função para remover ESP de um modelo
	local function removeESP(model)
		if highlights[model] then
			highlights[model]:Destroy()
			highlights[model] = nil
		end
	end
	
	-- Função para escanear e adicionar ESP em todos os personagens
	local function scanWorkspace()
		for _, model in pairs(Workspace:GetDescendants()) do
			if model:IsA("Model") and isValidCharacter(model) and espEnabled then
				createESP(model)
			end
		end
	end
	
	-- Função para ativar ESP
	local function enableESP()
		scanWorkspace()
	
		-- Monitora novos modelos adicionados
		Workspace.DescendantAdded:Connect(function(descendant)
			if espEnabled and descendant:IsA("Model") and isValidCharacter(descendant) then
				task.wait(0.1) -- Espera para garantir que o modelo está completo
				if descendant.Parent then
					createESP(descendant)
				end
			end
		end)
	
		-- Monitora jogadores
		Players.PlayerAdded:Connect(function(player)
			player.CharacterAdded:Connect(function(character)
				if espEnabled then
					createESP(character)
				end
			end)
		end)
	
		-- Adiciona ESP em jogadores existentes
		for _, player in pairs(Players:GetPlayers()) do
			if player.Character and player ~= localPlayer then
				createESP(player.Character)
			end
	
			player.CharacterAdded:Connect(function(character)
				if espEnabled then
					createESP(character)
				end
			end)
		end
	end
	
	-- Função para desativar ESP
	local function disableESP()
		for model, highlight in pairs(highlights) do
			highlight:Destroy()
		end
		highlights = {}
	end
	
	-- Toggle do ESP ao clicar no botão
	button.MouseButton1Click:Connect(function()
		espEnabled = not espEnabled
	
		if espEnabled then
			enableESP()
		else
			disableESP()
		end
	end)
end;
task.spawn(C_4b);
-- StarterGui.Painel do Mano.Menu.Visuais.esp.TextLabel.LocalScript
local function C_4e()
local script = G2L["4e"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_4e);
-- StarterGui.Painel do Mano.Menu.Visuais.t esp.LocalScript
local function C_50()
local script = G2L["50"];
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local localPlayer = Players.LocalPlayer
	local espEnabled = false
	local espConnections = {}
	local playerESPs = {}
	
	-- Função para criar o ESP visual em um personagem
	local function createESP(character, teamColor)
		if playerESPs[character] then return end
	
		local highlight = Instance.new("Highlight")
		highlight.Name = "TeamESP"
		highlight.Adornee = character
		highlight.FillColor = teamColor
		highlight.OutlineColor = teamColor
		highlight.FillTransparency = 0.5
		highlight.OutlineTransparency = 0
		highlight.Parent = character
	
		playerESPs[character] = highlight
	end
	
	-- Função para remover ESP de um personagem
	local function removeESP(character)
		if playerESPs[character] then
			playerESPs[character]:Destroy()
			playerESPs[character] = nil
		end
	end
	
	-- Função para verificar se um jogador é de outro time
	local function isEnemyTeam(player)
		if not localPlayer.Team or not player.Team then
			return false
		end
		return localPlayer.Team ~= player.Team
	end
	
	-- Função para aplicar ESP em um jogador específico
	local function applyESPToPlayer(player)
		local function setupCharacter(character)
			if not espEnabled then return end
			if not isEnemyTeam(player) then return end
	
			-- Aguarda o character carregar completamente
			if not character:FindFirstChild("HumanoidRootPart") then
				character:WaitForChild("HumanoidRootPart", 5)
			end
	
			local teamColor = player.Team.TeamColor.Color
			createESP(character, teamColor)
		end
	
		-- Aplica ESP no personagem atual
		if player.Character then
			setupCharacter(player.Character)
		end
	
		-- Monitora quando o jogador respawna
		local charConn = player.CharacterAdded:Connect(function(character)
			if espEnabled then
				task.wait(0.1) -- Pequeno delay para garantir que tudo carregou
				setupCharacter(character)
			end
		end)
	
		table.insert(espConnections, charConn)
	end
	
	-- Função para atualizar ESP de todos os jogadores
	local function updateAllESPs()
		for _, player in pairs(Players:GetPlayers()) do
			if player ~= localPlayer then
				if player.Character then
					local hasESP = playerESPs[player.Character] ~= nil
					local shouldHaveESP = isEnemyTeam(player)
	
					if shouldHaveESP and not hasESP then
						-- Adiciona ESP se não tiver
						local teamColor = player.Team and player.Team.TeamColor.Color or Color3.new(1, 0, 0)
						createESP(player.Character, teamColor)
					elseif not shouldHaveESP and hasESP then
						-- Remove ESP se não deveria ter
						removeESP(player.Character)
					end
				end
			end
		end
	end
	
	-- Função para ativar o ESP
	local function enableESP()
		espEnabled = true
	
		-- Aplica ESP em todos os jogadores existentes
		for _, player in pairs(Players:GetPlayers()) do
			if player ~= localPlayer then
				applyESPToPlayer(player)
			end
		end
	
		-- Monitora novos jogadores entrando
		local playerAddedConn = Players.PlayerAdded:Connect(function(player)
			if espEnabled then
				applyESPToPlayer(player)
			end
		end)
		table.insert(espConnections, playerAddedConn)
	
		-- Atualiza ESP quando o jogador local muda de time
		local teamChangedConn = localPlayer:GetPropertyChangedSignal("Team"):Connect(function()
			if espEnabled then
				task.wait(0.1)
				updateAllESPs()
			end
		end)
		table.insert(espConnections, teamChangedConn)
	
		-- Monitora mudanças de time dos outros jogadores
		local updateConn = RunService.Heartbeat:Connect(function()
			if espEnabled then
				for _, player in pairs(Players:GetPlayers()) do
					if player ~= localPlayer and player.Character then
						local esp = playerESPs[player.Character]
						local shouldHave = isEnemyTeam(player)
	
						if shouldHave and not esp then
							local teamColor = player.Team and player.Team.TeamColor.Color or Color3.new(1, 0, 0)
							createESP(player.Character, teamColor)
						elseif not shouldHave and esp then
							removeESP(player.Character)
						elseif esp and player.Team then
							-- Atualiza cor se mudou de time
							esp.FillColor = player.Team.TeamColor.Color
							esp.OutlineColor = player.Team.TeamColor.Color
						end
					end
				end
			end
		end)
		table.insert(espConnections, updateConn)
	end
	
	-- Função para desativar o ESP
	local function disableESP()
		espEnabled = false
	
		-- Remove todos os ESPs ativos
		for character, _ in pairs(playerESPs) do
			removeESP(character)
		end
	
		-- Desconecta todos os eventos
		for _, conn in pairs(espConnections) do
			conn:Disconnect()
		end
		espConnections = {}
	end
	
	-- Evento de clique no botão (toggle)
	button.MouseButton1Click:Connect(function()
		if espEnabled then
			disableESP()
		else
			enableESP()
		end
	end)
end;
task.spawn(C_50);
-- StarterGui.Painel do Mano.Menu.Visuais.t esp.TextLabel.LocalScript
local function C_53()
local script = G2L["53"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_53);
-- StarterGui.Painel do Mano.Menu.Visuais.l esp.LocalScript
local function C_55()
local script = G2L["55"];
	-- ESP de Linhas para Jogadores
	-- Script Local
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local LocalPlayer = Players.LocalPlayer
	local Camera = workspace.CurrentCamera
	
	-- ===== BOTÃO (NÃO MODIFICA UI) =====
	local PlayerGui = LocalPlayer:WaitForChild("PlayerGui")
	local ScreenGui = PlayerGui:WaitForChild("ScreenGui") -- altere se necessário
	local ToggleButton = ScreenGui:WaitForChild("ToggleButton") -- altere se necessário
	
	-- Tabela para armazenar as linhas de cada jogador
	local ESPLines = {}
	
	-- Configurações
	local CONFIG = {
		LineColor = Color3.fromRGB(255, 0, 0),
		LineThickness = 2,
		LineTransparency = 0.5,
		Enabled = false -- começa desligado
	}
	
	-- Remove ESP
	local function removeESP(player)
		if ESPLines[player] then
			if ESPLines[player].Line then
				ESPLines[player].Line:Remove()
			end
			ESPLines[player] = nil
		end
	end
	
	-- Cria ESP
	local function createESP(player)
		if player == LocalPlayer then return end
	
		removeESP(player)
	
		local line = Drawing.new("Line")
		line.Thickness = CONFIG.LineThickness
		line.Color = CONFIG.LineColor
		line.Transparency = CONFIG.LineTransparency
		line.Visible = false
	
		ESPLines[player] = {
			Line = line,
			Player = player
		}
	end
	
	-- Atualiza ESP
	local function updateESP()
		if not CONFIG.Enabled then return end
	
		local localChar = LocalPlayer.Character
		if not localChar then return end
	
		local localRoot = localChar:FindFirstChild("HumanoidRootPart")
		if not localRoot then return end
	
		local screenCenter = Vector2.new(
			Camera.ViewportSize.X / 2,
			Camera.ViewportSize.Y / 2
		)
	
		for player, espData in pairs(ESPLines) do
			local char = player.Character
			if char then
				local hum = char:FindFirstChild("Humanoid")
				local root = char:FindFirstChild("HumanoidRootPart")
	
				if hum and root and hum.Health > 0 then
					local pos, onScreen = Camera:WorldToViewportPoint(root.Position)
					if onScreen then
						espData.Line.From = screenCenter
						espData.Line.To = Vector2.new(pos.X, pos.Y)
						espData.Line.Visible = true
					else
						espData.Line.Visible = false
					end
				else
					espData.Line.Visible = false
				end
			else
				espData.Line.Visible = false
			end
		end
	end
	
	-- Toggle ESP
	local function toggleESP()
		CONFIG.Enabled = not CONFIG.Enabled
	
		if not CONFIG.Enabled then
			for _, espData in pairs(ESPLines) do
				espData.Line.Visible = false
			end
		end
	end
	
	-- ===== CLIQUE DO BOTÃO =====
	ToggleButton.MouseButton1Click:Connect(function()
		toggleESP()
	end)
	
	-- Player Added
	Players.PlayerAdded:Connect(function(player)
		player.CharacterAdded:Connect(function()
			createESP(player)
		end)
	
		if player.Character then
			createESP(player)
		end
	end)
	
	-- Player Removing
	Players.PlayerRemoving:Connect(function(player)
		removeESP(player)
	end)
	
	-- Jogadores já existentes
	for _, player in pairs(Players:GetPlayers()) do
		if player ~= LocalPlayer then
			createESP(player)
	
			player.CharacterAdded:Connect(function()
				createESP(player)
			end)
		end
	end
	
	-- Respawn local
	LocalPlayer.CharacterAdded:Connect(function()
		for _, player in pairs(Players:GetPlayers()) do
			if player ~= LocalPlayer then
				createESP(player)
			end
		end
	end)
	
	-- Loop
	RunService.RenderStepped:Connect(updateESP)
	
	-- Cleanup
	game:GetService("CoreGui").ChildRemoved:Connect(function()
		for _, espData in pairs(ESPLines) do
			if espData.Line then
				espData.Line:Remove()
			end
		end
	end)
	
end;
task.spawn(C_55);
-- StarterGui.Painel do Mano.Menu.Visuais.l esp.TextLabel.LocalScript
local function C_58()
local script = G2L["58"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_58);
-- StarterGui.Painel do Mano.Menu.Visuais.m esp.LocalScript
local function C_5a()
local script = G2L["5a"];
	local Players = game:GetService("Players")
	
	local LocalPlayer = Players.LocalPlayer
	local Button = script.Parent
	
	local espAtivo = false
	local billboards = {}
	
	-- Remove Billboard
	local function remover(player)
		if billboards[player] then
			billboards[player]:Destroy()
			billboards[player] = nil
		end
	end
	
	-- Cria BillboardGui
	local function criarBillboard(player, character)
		if not espAtivo then return end
		if player == LocalPlayer then return end
	
		remover(player)
	
		local head = character:WaitForChild("Head", 5)
		if not head then return end
	
		local billboard = Instance.new("BillboardGui")
		billboard.Name = "game.m"
		billboard.Adornee = head
		billboard.Size = UDim2.new(0, 200, 0, 50)
		billboard.StudsOffset = Vector3.new(0, 2.5, 0)
		billboard.AlwaysOnTop = true
		billboard.Parent = head
	
		local text = Instance.new("TextLabel")
		text.Size = UDim2.new(1, 0, 1, 0)
		text.BackgroundTransparency = 1
		text.TextScaled = true
		text.Font = Enum.Font.Sarpanch
		text.TextStrokeTransparency = 0.3
		text.Text = player.Name .. " [" .. (player.Team and player.Team.Name or "nil") .. "]"
		text.TextColor3 = player.TeamColor.Color
		text.Parent = billboard
	
		billboards[player] = billboard
	end
	
	-- Ativa ESP em todos
	local function ativarESP()
		for _, player in ipairs(Players:GetPlayers()) do
			if player.Character then
				criarBillboard(player, player.Character)
			end
	
			player.CharacterAdded:Connect(function(char)
				if espAtivo then
					task.wait(0.2)
					criarBillboard(player, char)
				end
			end)
	
			player:GetPropertyChangedSignal("Team"):Connect(function()
				if espAtivo and player.Character then
					criarBillboard(player, player.Character)
				end
			end)
		end
	end
	
	-- Remove ESP geral
	local function desativarESP()
		for _, billboard in pairs(billboards) do
			if billboard then billboard:Destroy() end
		end
		table.clear(billboards)
	end
	
	-- Player entrou
	Players.PlayerAdded:Connect(function(player)
		player.CharacterAdded:Connect(function(char)
			if espAtivo then
				task.wait(0.2)
				criarBillboard(player, char)
			end
		end)
	
		player:GetPropertyChangedSignal("Team"):Connect(function()
			if espAtivo and player.Character then
				criarBillboard(player, player.Character)
			end
		end)
	end)
	
	-- Clique do botão (Toggle)
	Button.MouseButton1Click:Connect(function()
		espAtivo = not espAtivo
	
		if espAtivo then
			ativarESP()
		else
			desativarESP()
		end
	end)
	
end;
task.spawn(C_5a);
-- StarterGui.Painel do Mano.Menu.Visuais.m esp.TextLabel.LocalScript
local function C_5d()
local script = G2L["5d"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_5d);
-- StarterGui.Painel do Mano.Menu.Visuais.d esp.LocalScript
local function C_5f()
local script = G2L["5f"];
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local localPlayer = Players.LocalPlayer
	local distanceEnabled = false
	local distanceConnections = {}
	local playerDistances = {}
	
	-- Função para criar o display de distância
	local function createDistanceDisplay(character)
		if playerDistances[character] then return end
	
		local rootPart = character:FindFirstChild("HumanoidRootPart")
		if not rootPart then return end
	
		-- Cria o BillboardGui
		local billboard = Instance.new("BillboardGui")
		billboard.Name = "DistanceDisplay"
		billboard.Adornee = rootPart
		billboard.Size = UDim2.new(0, 80, 0, 25)
		billboard.StudsOffset = Vector3.new(0, -3, 0)
		billboard.AlwaysOnTop = true
		billboard.Parent = character
	
		-- Cria o texto
		local textLabel = Instance.new("TextLabel")
		textLabel.Size = UDim2.new(1, 0, 1, 0)
		textLabel.BackgroundTransparency = 0.5
		textLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		textLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
		textLabel.TextStrokeTransparency = 0.5
		textLabel.TextScaled = true
		textLabel.Font = Enum.Font.GothamBold
		textLabel.Text = "0m"
		textLabel.Parent = billboard
	
		-- Arredonda as bordas
		local corner = Instance.new("UICorner")
		corner.CornerRadius = UDim.new(0, 4)
		corner.Parent = textLabel
	
		playerDistances[character] = {
			billboard = billboard,
			label = textLabel
		}
	end
	
	-- Função para remover display de distância
	local function removeDistanceDisplay(character)
		if playerDistances[character] then
			playerDistances[character].billboard:Destroy()
			playerDistances[character] = nil
		end
	end
	
	-- Função para calcular e atualizar distâncias
	local function updateDistances()
		local localChar = localPlayer.Character
		if not localChar then return end
	
		local localRoot = localChar:FindFirstChild("HumanoidRootPart")
		if not localRoot then return end
	
		for character, data in pairs(playerDistances) do
			if character and character.Parent then
				local targetRoot = character:FindFirstChild("HumanoidRootPart")
				if targetRoot then
					local distance = (localRoot.Position - targetRoot.Position).Magnitude
					local distanceInMeters = math.floor(distance)
					data.label.Text = distanceInMeters .. "m"
				end
			else
				-- Remove se o personagem foi destruído
				removeDistanceDisplay(character)
			end
		end
	end
	
	-- Função para aplicar display em um jogador
	local function applyDistanceToPlayer(player)
		local function setupCharacter(character)
			if not distanceEnabled then return end
	
			-- Aguarda o character carregar
			if not character:FindFirstChild("HumanoidRootPart") then
				character:WaitForChild("HumanoidRootPart", 5)
			end
	
			createDistanceDisplay(character)
		end
	
		-- Aplica no personagem atual
		if player.Character then
			setupCharacter(player.Character)
		end
	
		-- Monitora respawn
		local charConn = player.CharacterAdded:Connect(function(character)
			if distanceEnabled then
				task.wait(0.1)
				setupCharacter(character)
			end
		end)
	
		table.insert(distanceConnections, charConn)
	end
	
	-- Função para ativar os displays
	local function enableDistance()
		distanceEnabled = true
	
		-- Aplica em todos os jogadores existentes
		for _, player in pairs(Players:GetPlayers()) do
			if player ~= localPlayer then
				applyDistanceToPlayer(player)
			end
		end
	
		-- Monitora novos jogadores
		local playerAddedConn = Players.PlayerAdded:Connect(function(player)
			if distanceEnabled then
				applyDistanceToPlayer(player)
			end
		end)
		table.insert(distanceConnections, playerAddedConn)
	
		-- Atualiza distâncias continuamente
		local updateConn = RunService.RenderStepped:Connect(function()
			if distanceEnabled then
				updateDistances()
			end
		end)
		table.insert(distanceConnections, updateConn)
	end
	
	-- Função para desativar os displays
	local function disableDistance()
		distanceEnabled = false
	
		-- Remove todos os displays
		for character, _ in pairs(playerDistances) do
			removeDistanceDisplay(character)
		end
	
		-- Desconecta eventos
		for _, conn in pairs(distanceConnections) do
			conn:Disconnect()
		end
		distanceConnections = {}
	end
	
	-- Evento de clique no botão (toggle)
	button.MouseButton1Click:Connect(function()
		if distanceEnabled then
			disableDistance()
		else
			enableDistance()
		end
	end)
end;
task.spawn(C_5f);
-- StarterGui.Painel do Mano.Menu.Visuais.d esp.TextLabel.LocalScript
local function C_62()
local script = G2L["62"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_62);
-- StarterGui.Painel do Mano.Menu.Visuais.mira fixa.LocalScript
local function C_64()
local script = G2L["64"];
	-- Center Dot controlável por botão
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local DOT_SIZE = 8
	local DOT_COLOR = Color3.fromRGB(255, 255, 255)
	
	local player = Players.LocalPlayer
	local playerGui = player:WaitForChild("PlayerGui")
	
	-- Espera câmera
	local camera
	repeat
		camera = workspace.CurrentCamera
		RunService.RenderStepped:Wait()
	until camera
	
	-- ScreenGui
	local gui = Instance.new("ScreenGui")
	gui.Name = "CenterDotGui"
	gui.ResetOnSpawn = false
	gui.DisplayOrder = 1000
	pcall(function() gui.IgnoreGuiInset = true end)
	gui.Parent = playerGui
	
	-- Dot
	local dot = Instance.new("Frame")
	dot.Name = "CenterDot"
	dot.Size = UDim2.new(0, DOT_SIZE, 0, DOT_SIZE)
	dot.AnchorPoint = Vector2.new(0.5, 0.5)
	dot.BackgroundColor3 = DOT_COLOR
	dot.BorderSizePixel = 0
	dot.Visible = false
	dot.ZIndex = 9999
	dot.Parent = gui
	
	local corner = Instance.new("UICorner")
	corner.CornerRadius = UDim.new(1, 0)
	corner.Parent = dot
	
	-- Atualiza posição
	local function update()
		local vs = camera.ViewportSize
		dot.Position = UDim2.new(0, vs.X / 2, 0, vs.Y / 2)
	end
	
	RunService.RenderStepped:Connect(function()
		if dot.Visible then
			update()
		end
	end)
	
	-- BOTÃO
	local button = script.Parent -- TextButton ou ImageButton
	
	button.Activated:Connect(function()
		dot.Visible = not dot.Visible
		if dot.Visible then
			update()
		end
	end)
	
end;
task.spawn(C_64);
-- StarterGui.Painel do Mano.Menu.Visuais.mira fixa.TextLabel.LocalScript
local function C_67()
local script = G2L["67"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_67);
-- StarterGui.Painel do Mano.Menu.Visuais.SetFov.LocalScript
local function C_6a()
local script = G2L["6a"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_6a);
-- StarterGui.Painel do Mano.Menu.Visuais.FOV.LocalScript
local function C_6c()
local script = G2L["6c"];
	local button = script.Parent
	local textbox = button.Parent:WaitForChild("SetFov")
	
	local Camera = workspace.CurrentCamera
	
	button.MouseButton1Click:Connect(function()
		local text = textbox.Text
		local value = tonumber(text)
	
		if value then
			Camera.FieldOfView = math.clamp(value, 1, 120)
			print("FOV alterado para:", value)
		else
			warn("Valor inválido na caixa de texto!")
		end
	end)
	
end;
task.spawn(C_6c);
-- StarterGui.Painel do Mano.Menu.Visuais.FOV.TextLabel.LocalScript
local function C_6f()
local script = G2L["6f"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_6f);
-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
local function C_72()
local script = G2L["72"];
	local Lighting = game:GetService("Lighting")
	local button = script.Parent
	
	-- Guarda o estado original dos efeitos
	local effectsCache = {}
	local effectsDisabled = false
	
	-- Tipos de efeitos suportados
	local EFFECT_CLASSES = {
		BloomEffect = true,
		BlurEffect = true,
		ColorCorrectionEffect = true,
		SunRaysEffect = true,
		DepthOfFieldEffect = true,
		Atmosphere = true
	}
	
	local function disableEffects()
		effectsCache = {}
	
		for _, obj in ipairs(Lighting:GetChildren()) do
			if EFFECT_CLASSES[obj.ClassName] then
				if obj:IsA("Atmosphere") then
					-- Atmosphere não tem Enabled
					effectsCache[obj] = obj.Parent
					obj.Parent = nil
				else
					effectsCache[obj] = obj.Enabled
					obj.Enabled = false
				end
			end
		end
	
		effectsDisabled = true
	end
	
	local function enableEffects()
		for obj, state in pairs(effectsCache) do
			if obj and obj.Parent == nil and obj:IsA("Atmosphere") then
				obj.Parent = Lighting
			elseif obj and obj.Parent then
				obj.Enabled = state
			end
		end
	
		effectsCache = {}
		effectsDisabled = false
	end
	
	button.MouseButton1Click:Connect(function()
		if effectsDisabled then
			enableEffects()
			button.Text = ""
		else
			disableEffects()
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_72);
-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
local function C_75()
local script = G2L["75"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_75);
-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
local function C_77()
local script = G2L["77"];
	local button = script.Parent
	
	local particlesDisabled = false
	local cache = {}
	
	-- Classes de partículas
	local PARTICLE_CLASSES = {
		ParticleEmitter = true,
		Fire = true,
		Smoke = true,
		Trail = true,
		Sparkles = true
	}
	
	local function disableParticles()
		cache = {}
	
		for _, obj in ipairs(workspace:GetDescendants()) do
			if PARTICLE_CLASSES[obj.ClassName] then
				-- Alguns usam Enabled, outros não
				if obj:IsA("ParticleEmitter") or obj:IsA("Trail") then
					cache[obj] = obj.Enabled
					obj.Enabled = false
				elseif obj:IsA("Fire") or obj:IsA("Smoke") or obj:IsA("Sparkles") then
					cache[obj] = obj.Enabled
					obj.Enabled = false
				end
			end
		end
	
		particlesDisabled = true
	end
	
	local function enableParticles()
		for obj, state in pairs(cache) do
			if obj and obj.Parent then
				obj.Enabled = state
			end
		end
	
		cache = {}
		particlesDisabled = false
	end
	
	button.MouseButton1Click:Connect(function()
		if particlesDisabled then
			enableParticles()
			button.Text = ""
		else
			disableParticles()
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_77);
-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
local function C_7a()
local script = G2L["7a"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_7a);
-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
local function C_7c()
local script = G2L["7c"];
	local Lighting = game:GetService("Lighting")
	local button = script.Parent
	
	local shadowsDisabled = false
	local originalGlobalShadows = Lighting.GlobalShadows
	local originalTechnology = Lighting.Technology
	
	local function disableShadows()
		originalGlobalShadows = Lighting.GlobalShadows
		originalTechnology = Lighting.Technology
	
		Lighting.GlobalShadows = false
		Lighting.Technology = Enum.Technology.Compatibility
	
		shadowsDisabled = true
	end
	
	local function enableShadows()
		Lighting.GlobalShadows = originalGlobalShadows
		Lighting.Technology = originalTechnology
	
		shadowsDisabled = false
	end
	
	button.MouseButton1Click:Connect(function()
		if shadowsDisabled then
			enableShadows()
			button.Text = ""
		else
			disableShadows()
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_7c);
-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
local function C_7f()
local script = G2L["7f"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_7f);
-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
local function C_81()
local script = G2L["81"];
	local button = script.Parent
	local workspace = game:GetService("Workspace")
	
	local plasticMode = false
	local cache = {}
	
	local function disableMaterials()
		cache = {}
	
		for _, obj in ipairs(workspace:GetDescendants()) do
			if obj:IsA("BasePart") then
				cache[obj] = {
					Material = obj.Material,
					MaterialVariant = obj.MaterialVariant,
					Reflectance = obj.Reflectance
				}
	
				obj.Material = Enum.Material.Plastic
				obj.MaterialVariant = ""
				obj.Reflectance = 0
			end
		end
	
		plasticMode = true
	end
	
	local function enableMaterials()
		for obj, data in pairs(cache) do
			if obj and obj.Parent then
				obj.Material = data.Material
				obj.MaterialVariant = data.MaterialVariant
				obj.Reflectance = data.Reflectance
			end
		end
	
		cache = {}
		plasticMode = false
	end
	
	button.MouseButton1Click:Connect(function()
		if plasticMode then
			enableMaterials()
			button.Text = ""
		else
			disableMaterials()
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_81);
-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
local function C_84()
local script = G2L["84"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_84);
-- StarterGui.Painel do Mano.Menu.Fps.eff.LocalScript
local function C_86()
local script = G2L["86"];
	-- SERVIÇOS
	local Players = game:GetService("Players")
	local Lighting = game:GetService("Lighting")
	local SoundService = game:GetService("SoundService")
	local RunService = game:GetService("RunService")
	local player = Players.LocalPlayer
	local button = script.Parent
	local workspace = game:GetService("Workspace")
	
	-- ESTADO
	local potatoMode = false
	local cache = {}
	local connections = {}
	
	-- ==============================
	-- FUNÇÕES DE DESATIVAÇÃO
	-- ==============================
	
	local function disableVisualEffects()
		for _, obj in ipairs(Lighting:GetChildren()) do
			if obj:IsA("PostEffect") then
				cache[obj] = obj.Enabled
				obj.Enabled = false
			elseif obj:IsA("Atmosphere") then
				cache[obj] = obj.Parent
				obj.Parent = nil
			end
		end
	
		cache.GlobalShadows = Lighting.GlobalShadows
		cache.Technology = Lighting.Technology
	
		Lighting.GlobalShadows = false
		Lighting.Technology = Enum.Technology.Compatibility
	end
	
	local function disableParticles()
		for _, obj in ipairs(workspace:GetDescendants()) do
			if obj:IsA("ParticleEmitter")
				or obj:IsA("Trail")
				or obj:IsA("Fire")
				or obj:IsA("Smoke")
				or obj:IsA("Sparkles") then
				cache[obj] = obj.Enabled
				obj.Enabled = false
			end
		end
	end
	
	local function disableMaterialsAndTextures()
		for _, obj in ipairs(workspace:GetDescendants()) do
			if obj:IsA("BasePart") then
				cache[obj] = {
					Material = obj.Material,
					MaterialVariant = obj.MaterialVariant,
					Reflectance = obj.Reflectance
				}
	
				obj.Material = Enum.Material.Plastic
				obj.MaterialVariant = ""
				obj.Reflectance = 0
			elseif obj:IsA("Texture")
				or obj:IsA("Decal")
				or obj:IsA("SurfaceAppearance") then
				cache[obj] = obj.Transparency or 0
				obj.Transparency = 1
			end
		end
	end
	
	local function disableSounds()
		cache.SoundVolume = SoundService.Volume
		SoundService.Volume = 0
	
		for _, sound in ipairs(workspace:GetDescendants()) do
			if sound:IsA("Sound") then
				cache[sound] = sound.Volume
				sound.Volume = 0
			end
		end
	end
	
	local function reduceRendering()
		settings().Rendering.QualityLevel = Enum.QualityLevel.Level01
	end
	
	-- ==============================
	-- SISTEMA DE OTIMIZAÇÃO CONTÍNUA
	-- ==============================
	
	local function startOptimizer()
		connections.descendant = workspace.DescendantAdded:Connect(function(obj)
			if not potatoMode then return end
	
			if obj:IsA("BasePart") then
				obj.Material = Enum.Material.Plastic
				obj.MaterialVariant = ""
				obj.Reflectance = 0
			elseif obj:IsA("ParticleEmitter")
				or obj:IsA("Trail")
				or obj:IsA("Fire")
				or obj:IsA("Smoke")
				or obj:IsA("Sparkles") then
				obj.Enabled = false
			elseif obj:IsA("Texture")
				or obj:IsA("Decal")
				or obj:IsA("SurfaceAppearance") then
				obj.Transparency = 1
			elseif obj:IsA("Sound") then
				obj.Volume = 0
			end
		end)
	
		connections.loop = RunService.RenderStepped:Connect(function()
			if potatoMode then
				Lighting.GlobalShadows = false
			end
		end)
	end
	
	local function stopOptimizer()
		for _, conn in pairs(connections) do
			conn:Disconnect()
		end
		connections = {}
	end
	
	-- ==============================
	-- RESTAURAÇÃO
	-- ==============================
	
	local function restoreAll()
		for obj, data in pairs(cache) do
			if typeof(data) == "boolean" and obj:IsA("PostEffect") then
				obj.Enabled = data
			elseif typeof(data) == "table" and obj:IsA("BasePart") then
				obj.Material = data.Material
				obj.MaterialVariant = data.MaterialVariant
				obj.Reflectance = data.Reflectance
			elseif typeof(data) == "number" and obj:IsA("Sound") then
				obj.Volume = data
			elseif obj == "GlobalShadows" then
				Lighting.GlobalShadows = data
			elseif obj == "Technology" then
				Lighting.Technology = data
			end
		end
	
		if cache.SoundVolume then
			SoundService.Volume = cache.SoundVolume
		end
	
		cache = {}
		stopOptimizer()
	end
	
	-- ==============================
	-- BOTÃO
	-- ==============================
	
	button.MouseButton1Click:Connect(function()
		if potatoMode then
			restoreAll()
			potatoMode = false
			button.Text = ""
		else
			cache = {}
			disableVisualEffects()
			disableParticles()
			disableMaterialsAndTextures()
			disableSounds()
			reduceRendering()
			startOptimizer()
	
			potatoMode = true
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_86);
-- StarterGui.Painel do Mano.Menu.Fps.eff.TextLabel.LocalScript
local function C_89()
local script = G2L["89"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_89);
-- StarterGui.Painel do Mano.Menu.Fps.FPSDisplay.LocalScript
local function C_8b()
local script = G2L["8b"];
	local waitTime = 0.3
	
	local lastUpdateTime = tick()
	
	local deltaTimesInterval = {}
	
	local numDP = 1
	
	game:GetService("RunService").RenderStepped:Connect(function(deltaTime)
	
		local now = tick()
		local timePassed = now - lastUpdateTime
	
		table.insert(deltaTimesInterval, deltaTime)
	
		if timePassed >= waitTime then
	
			local totalDeltaTime = 0		
			for _, deltaTimeRecorded in pairs(deltaTimesInterval) do
				totalDeltaTime += deltaTimeRecorded
			end
	
			local numDeltas = #deltaTimesInterval
	
			local avgDeltaTime = totalDeltaTime / numDeltas
	
			local framesPerSecond = 1 / avgDeltaTime
			local formattedFPS = string.format("%." .. numDP .. "f", framesPerSecond)
	
			table.clear(deltaTimesInterval)
	
			script.Parent.Text = " " .. formattedFPS
	
			lastUpdateTime = now
		end
	end)
end;
task.spawn(C_8b);
-- StarterGui.Painel do Mano.Menu.Fps.FPSDisplay.LocalScript
local function C_8d()
local script = G2L["8d"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_8d);
-- StarterGui.Painel do Mano.Menu.Fps.TextLabel.LocalScript
local function C_8f()
local script = G2L["8f"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_8f);
-- StarterGui.Painel do Mano.Menu.Outers.Pedrinhuu On Top.LocalScript
local function C_93()
local script = G2L["93"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_93);
-- StarterGui.Painel do Mano.Menu.Close.LocalScript
local function C_9b()
local script = G2L["9b"];
	local button = script.Parent
	local screenGui = button:FindFirstAncestorOfClass("ScreenGui")
	
	button.Activated:Connect(function()
		if screenGui then
			screenGui:Destroy()
		end
	end)
	
end;
task.spawn(C_9b);
-- StarterGui.Painel do Mano.Menu.Min.LocalScript
local function C_9d()
local script = G2L["9d"];
	local screenGui = script.Parent.Parent.Parent
	local menu = screenGui:WaitForChild("Menu")
	local openButton = screenGui:WaitForChild("Open")
	
	script.Parent.MouseButton1Click:Connect(function()
		menu.Visible = false
		openButton.Visible = true
	end)
	
end;
task.spawn(C_9d);
-- StarterGui.Painel do Mano.Open. botao
local function C_9f()
local script = G2L["9f"];
	local button = script.Parent
	local UIS = game:GetService("UserInputService")
	
	local dragging = false
	local dragStart
	local startPos
	local moved = false
	
	local function update(input)
		local delta = input.Position - dragStart
		button.Position = UDim2.new(
			startPos.X.Scale,
			startPos.X.Offset + delta.X,
			startPos.Y.Scale,
			startPos.Y.Offset + delta.Y
		)
	end
	
	button.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			moved = false
			dragStart = input.Position
			startPos = button.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	button.InputChanged:Connect(function(input)
		if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
			moved = true
			update(input)
		end
	end)
	
	button.Activated:Connect(function()
		if moved then return end -- BLOQUEIA clique se foi arrasto
	
		local screenGui = button.Parent
		local menu = screenGui:WaitForChild("Menu")
	
		menu.Visible = true
		button.Visible = false
	end)
	
end;
task.spawn(C_9f);
-- StarterGui.Painel do Mano.Open.LocalScript
local function C_a0()
local script = G2L["a0"];
	local screenGui = script.Parent.Parent
	local menu = screenGui:WaitForChild("Menu")
	
	script.Parent.MouseButton1Click:Connect(function()
		menu.Visible = true
		script.Parent.Visible = false
	end)
	
end;
task.spawn(C_a0);

return G2L["1"], require;

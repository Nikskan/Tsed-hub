while wait(1) do
    for _, v in pairs(workspace:GetChildren()) do
        if v:IsA("Part") then
            print(v.Name .. " encontrado!")
        end
    end
end

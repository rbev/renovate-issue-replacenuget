# 33635

## Current behavior

Renovate will edit Directory.Pacakges.props correctly and ignore csproj files

## Expected behavior

Directory.Pacakges.props should become 

```
 <ItemGroup>
    <PackageVersion Include="AwesomeAssertions" Version="7.0.0" />
  </ItemGroup>
```

Project1.csproj should become
```
  <ItemGroup>
    <PackageReference Include="AwesomeAssertions"/>
  </ItemGroup>
```


## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/33635

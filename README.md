﻿ # CafeBazaarInstallUp
<?xml version="1.0" encoding="utf-8"?>

<Project ToolsVersion="14.0" DefaultTargets="Build" xmlns="http://schemas.microsoft.com/developer/msbuild/2003">

  <Import Project="$(MSBuildExtensionsPath)\$(MSBuildToolsVersion)\Microsoft.Common.props" Condition="Exists('$(MSBuildExtensionsPath)\$(MSBuildToolsVersion)\Microsoft.Common.props')" />

  <PropertyGroup>

    <Configuration Condition=" '$(Configuration)' == '' ">Debug</Configuration>

    <Platform Condition=" '$(Platform)' == '' ">AnyCPU</Platform>

    <ProjectGuid>{2CFD29BF-A35C-45B6-9F51-DAE244836FC2}</ProjectGuid>

    <OutputType>WinExe</OutputType>

    <AppDesignerFolder>Properties</AppDesignerFolder>

    <RootNamespace>CafeBazaarInstallUp</RootNamespace>

    <AssemblyName>CafeBazaarInstallUp</AssemblyName>

    <TargetFrameworkVersion>v4.5.2</TargetFrameworkVersion>

    <FileAlignment>512</FileAlignment>

    <AutoGenerateBindingRedirects>true</AutoGenerateBindingRedirects>

  </PropertyGroup>

  <PropertyGroup Condition=" '$(Configuration)|$(Platform)' == 'Debug|AnyCPU' ">

    <PlatformTarget>AnyCPU</PlatformTarget>

    <DebugSymbols>true</DebugSymbols>

    <DebugType>full</DebugType>

    <Optimize>false</Optimize>

    <OutputPath>bin\Debug\</OutputPath>

    <DefineConstants>DEBUG;TRACE</DefineConstants>

    <ErrorReport>prompt</ErrorReport>

    <WarningLevel>4</WarningLevel>

  </PropertyGroup>

  <PropertyGroup Condition=" '$(Configuration)|$(Platform)' == 'Release|AnyCPU' ">

    <PlatformTarget>AnyCPU</PlatformTarget>

    <DebugType>pdbonly</DebugType>

    <Optimize>true</Optimize>

    <OutputPath>bin\Release\</OutputPath>

    <DefineConstants>TRACE</DefineConstants>

    <ErrorReport>prompt</ErrorReport>

    <WarningLevel>4</WarningLevel>

  </PropertyGroup>

  <PropertyGroup>

    <ApplicationIcon>kiqthx.ico</ApplicationIcon>

  </PropertyGroup>

  <ItemGroup>

    <Reference Include="Newtonsoft.Json, Version=12.0.0.0, Culture=neutral, PublicKeyToken=30ad4fe6b2a6aeed, processorArchitecture=MSIL">

      <HintPath>..\packages\Newtonsoft.Json.12.0.3\lib\net45\Newtonsoft.Json.dll</HintPath>

      <Private>True</Private>

    </Reference>

    <Reference Include="RestSharp, Version=106.0.0.0, Culture=neutral, PublicKeyToken=598062e77f915f75, processorArchitecture=MSIL">

      <HintPath>..\packages\RestSharp.106.10.1\lib\net452\RestSharp.dll</HintPath>

      <Private>True</Private>

    </Reference>

    <Reference Include="System" />

    <Reference Include="System.Core" />

    <Reference Include="System.Web" />

    <Reference Include="System.Xml.Linq" />

    <Reference Include="System.Data.DataSetExtensions" />

    <Reference Include="Microsoft.CSharp" />

    <Reference Include="System.Data" />

    <Reference Include="System.Deployment" />

    <Reference Include="System.Drawing" />

    <Reference Include="System.Net.Http" />

    <Reference Include="System.Windows.Forms" />

    <Reference Include="System.Xml" />

  </ItemGroup>

  <ItemGroup>

    <Compile Include="Form1.cs">

      <SubType>Form</SubType>

    </Compile>

    <Compile Include="Form1.Designer.cs">

      <DependentUpon>Form1.cs</DependentUpon>

    </Compile>

    <Compile Include="Program.cs" />

    <Compile Include="Properties\AssemblyInfo.cs" />

    <Compile Include="Request.cs" />

    <EmbeddedResource Include="Form1.resx">

      <DependentUpon>Form1.cs</DependentUpon>

    </EmbeddedResource>

    <EmbeddedResource Include="Properties\Resources.resx">

      <Generator>ResXFileCodeGenerator</Generator>

      <LastGenOutput>Resources.Designer.cs</LastGenOutput>

      <SubType>Designer</SubType>

    </EmbeddedResource>

    <Compile Include="Properties\Resources.Designer.cs">

      <AutoGen>True</AutoGen>

      <DependentUpon>Resources.resx</DependentUpon>

      <DesignTime>True</DesignTime>

    </Compile>

    <None Include="packages.config" />

    <None Include="Properties\Settings.settings">

      <Generator>SettingsSingleFileGenerator</Generator>

      <LastGenOutput>Settings.Designer.cs</LastGenOutput>

    </None>

    <Compile Include="Properties\Settings.Designer.cs">

      <AutoGen>True</AutoGen>

      <DependentUpon>Settings.settings</DependentUpon>

      <DesignTimeSharedInput>True</DesignTimeSharedInput>

    </Compile>

  </ItemGroup>

  <ItemGroup>

    <None Include="App.config" />

  </ItemGroup>

  <ItemGroup>

    <Content Include="kiqthx.ico" />

  </ItemGroup>

  <Import Project="$(MSBuildToolsPath)\Microsoft.CSharp.targets" />

  <!-- To modify your build process, add your task inside one of the targets below and uncomment it. 

       Other similar extension points exist, see Microsoft.Common.targets.

  <Target Name="BeforeBuild">

  </Target>

  <Target Name="AfterBuild">

  </Target>

  -->

</Project>را

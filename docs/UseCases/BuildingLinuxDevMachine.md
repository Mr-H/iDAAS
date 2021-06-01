@{
    ViewBag.Title = "Building a Development Machine";
    Layout = "_Layout";
}
<div class="text-center">
    <h4 class="display-6">Building a Development Machine for CentOS Stream or RHEL 8.3</h4>
</div>
<div align="left">
    <br>
    <p>
        For this specific development image I started with RHEL 8.3; however, I also ran the on RHEL 8.2. Keep
        in mind that your RHEL VM will only be good for 2-3 months as subscriptions can lapse and must be renewed
        through the subscription manager. Base RHEL install, update subscription manager and patch. As for the install 
        typically the installs are the Server with GUI where lots of development tools and libraries are selected.
    </p>
     <h6 class="display-6"><u>Tools/Utilities</u></h6>
    <p>
        The ONLY development lanuage required for iDaaS specifically is Java SDK. The other development
        languages are used for a variety of efforts and needs. We don't cover Python in this section but those
        instructions can be easily found online.
    </p>
    <li>Maven</li>
    <p>
        This is needed on development machines and is the central repository management tool.
         From the command line: <br>
                sudo dnf install maven<br>
    </p>
   <h6 class="display-6"><u>Development Language(s)</u></h6>
    <p>
        The ONLY development lanuage required for iDaaS specifically is Java SDK. The other development
        languages are used for a variety of efforts and needs. We don't cover Python in this section but those
        instructions can be easily found online.
    </p>
    <li>Java SDK</li>
    <p>
        Platform comes with OpenJDK 8. Based on needs feel free to update system to (not just JREs) as you need.
        For this environment we will install Java OpenJDK 11. We have also had committers and resources leveraging
        iDaaS running Open JDK 11, 13, 14 and 15 as wekk, As with everything it is critical to make sure
        that you only run approved technologies. <br>
        From the command line:<br>
        yum install java-11-openjdk-devel<br>
        Switching Java versions is managed by <br>
        sudo update-alternatives --config java<br>
    </p>
    <li>.Net Core</li>
    <p>
        While not currently used within iDaaS there are plans to start leveraging it in 2021.
        <br>
        <a href="https://docs.microsoft.com/en-us/dotnet/core/install/linux" target="_blank">.Net Core Linux</a><br>
        <a href="https://docs.microsoft.com/en-us/dotnet/core/install/linux-rhel" target="_blank">.Net Core on Linux</a><br>
        From the command line: <br>
        sudo dnf install dotnet-sdk-5.0<br>
        sudo dnf install dotnet-sdk-3.1<br>
    </p>
    <li>GoLang</li>
    <p>
        From the command line: <br>
        sudo dnf install go<br>
    </p>
    <li>Ruby</li>
    <p>
        From the command line: <br>
        sudo dnf install ruby<br>
    </p>
    <br/>
       <h6 class="display-6"><u>Development Tooling</u></h6>
        <p>
            These specific steps focus around IntelliJ, numerous contributors and resources working with iDaaS use some
            flavor of IntelliJ. For simplicity we will download the files to /username/home/Downloads.
        </p>
        <li>Toolbox App</li>
        <p>
           Download the <a href="http://www.jetbrains.com/toolboxapp" target="_blank">.IntelliJ Tolbox App Download</a> for the link.<br>
         <ol>
          <li>cd /user/home/Downloads</li>
          <li>sudo tar -xvf jetbrains-toolbox-releasenumber.tar.gz -C /opt </li>
          <li>./jetbrains-toolbox-releasenumber</li>
           </ol> 
           <p>Now you can install all the development tools you need to leverage, clearly within Community edition or license you may have purchased</p>
        </p>
</div>

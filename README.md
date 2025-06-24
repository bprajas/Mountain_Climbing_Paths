\section*{Sources and Code Repository}

This project draws on a variety of theoretical and practical sources. The following references and datasets were used to build the models and simulate terrain:

\begin{itemize}
    \item \textbf{Digital Elevation Models (DEMs):} NASA Shuttle Radar Topography Mission (SRTMGL1 V3)
    \item \textbf{Snow Cover Data:} MODIS (Moderate Resolution Imaging Spectroradiometer)
    \item \textbf{Weather and Storm Data:} ERA5 Reanalysis from the European Centre for Medium-Range Weather Forecasts (ECMWF)
    \item \textbf{Empirical Hiking Model:} Tobler's Hiking Function
    \item \textbf{Mathematical Frameworks:} Euler--Lagrange equations, Multivariable Calculus, Variational Calculus
    \item \textbf{Programming Libraries:} Python, NumPy, SciPy, Matplotlib
\end{itemize}

\subsection*{Code Repository}
All code used for path simulations, visualisation, and terrain processing is available at the following GitHub repository:

\begin{quote}
\texttt{https://github.com/PrajasBharadwaj/Mountain-Path-Optimisation}
\end{quote}

The repository contains scripts for:
\begin{itemize}
    \item Parametric baseline path computation
    \item Geodesic solver via numerical Euler--Lagrange
    \item Tobler's hiking time minimisation
    \item Real DEM processing and environmental overlay integration
    \item 2D/3D path plotting and analysis
\end{itemize}
